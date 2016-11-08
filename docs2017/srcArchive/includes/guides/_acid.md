##AcID

ACID is an acronym for [atomic](acid.html#acid_atomic), [consistent](acid.html#acid_consistent), [isolated](acid.html#acid_isolated), [durable](acid.html#acid_durable), simply a set of properties which guarantee that transactions with a database are processed and reported reliably. Cloudant is AcID: the “c” is lowercase because Cloudant is [eventually consistent](cap_theorem.html) rather than strongly consistent.

### Atomic

<div id="acid_atomic"></div>

Atomic is just another way of saying cannot be divided. All this means is that if one part of a process fails, the whole process fails.
The failure helps ensure that the database remains in a consistent state. For example, a request to modify a document only reports success after the change has been written to disk.

### Consistent

<div id="acid_consistent"></div>

Cloudant is eventually consistent, such that any change will propagate to the whole cluster within milliseconds, but will not wait for that propagation before reporting success. 

### Isolated

<div id="acid_isolated"></div>

Cloudant is lockless, so that even simultaneous reads and writes will not delay or impact other reads and writes. Isolation just means that concurrent processes like this result in a state that would be obtained if things happened one at a time.

### Durable

<div id="acid_durable"></div>

Durability ensures that changes remain once committed, even with power failures or other errors. Document updates and insertions are written to disk before the request is considered complete.

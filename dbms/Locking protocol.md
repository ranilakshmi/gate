# Lock based systems

# Locks:
 - Shared locks : If a transaction has obtained a shared lock (denoted by S) on an item then it can read the item but not write.
 - Exclusive lock : If a transaction has obtained an exclusive-mode lock (denoted
by X) on an item , then it can both read and write that item.

## Two-phase locking protocol
- This protocol requires that each transaction issue lock and unlock requests in two phases:
1. Growing phase. A transaction may obtain locks, but may not release any lock.
2. Shrinking phase. A transaction may release locks, but may not obtain any new locks.

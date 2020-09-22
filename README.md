# Friends on Bus

There are `n` **groups of friends**, and each group is numbered from `1` to `n` . The `i`-th group contains `a_i` people.
 They live near a bus stop, and only a single bus operates on this route. An empty bus arrives at the bus stop and all the groups want to travel by the bus.

However, **group of friends** do not want to get separated. So they enter the bus only if the bus can carry the entire group.

Moreover, the groups do not want to change their relative positioning while travelling.
In other words, group `3` cannot travel by bus, unless group `1` and group `2` have either:
1. already traveled by the bus in the previous trip;
1. they are also sitting inside the bus at present.

You are given that a bus of size `x` can carry `x` people simultaneously.

 Find the size `x` of the bus so that:
1. the bus can transport all the groups;
1. every time when the bus starts from the bus station, there is no empty space in the bus (i.e. the total number of people present inside the bus is equal to `x`).

# Example

### Input Format

The first line contains an integer `n`(`1` <= `n` <= `10^5`). The second line contains `n` space-separated integers `a_1`, `a_2`, ..., `a_n` (`1` <= `a_i` <= `10^4`).

### Output Format

Print all possible sizes of the bus in an increasing order.

### Sample Input

```
8
3 2 1 1 1 2 1 1
```
### Sample Output

```
3 4 6 12
```

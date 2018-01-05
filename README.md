# ARP Protocol Design


1. The ARP protocol uses the the next-hop address and the interface number,
found in the routing table, to find the physical address of the next hop. Consider a
certain router Ri whose routing table has only three columns: mask, network address,
and next-hop address, i.e. the column with the interface numbers has been deleted.
(Note that only the column with the info on the interfaces has been removed not
the interfaces themselves, i.e. the network configuration has not changed.) Does
the ARP protocol still work? If not, how to modify this protocol to make it work?
Does your modification affect the network performance?

2. The ARP reply is used to update the ARP cache table. Can the ARP request
be also used to update this table? If so, how?

3. Two network administrators argue about setting an optimal time-out T for
the ARP cache table of a certain router. The first administrator thinks that T=t1 is
satisfactory, the other one claims that T=t2 is much better. Propose a set of criteria to
evaluate which of them is right. (Maybe both are wrong?) Which of these criteria is
the most important from your point of view?


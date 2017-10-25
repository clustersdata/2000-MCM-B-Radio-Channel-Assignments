# 2000-MCM-B-Radio-Channel-Assignments


We seek to model the assignment of radio channels to a symmetric network of transmitter locations over a large planar area, so as to avoid interference. One basic approach is to partition the region into regular hexagons in a grix (honeycomb-style), as shown in Figure 1, where a transmitter is located at the center of each hexagon.

An interval of the frequency spectrum is to be alloted for transmitter frequencies. The interval will be divided into regularly spaced channels, which we represent by integers 1,2,3, … . Each transmitter wil be assigned one positive integer channel. The same channel can be used at many locations, provided that interference from nearby transmitters is avoided.

Our goal is to minimize the width of the interval in the frequency spectrum that is needed to assugn channels subject to some constraints. This is achieved with the concept of a span. The span is the minimum, over all assignments satisfying the constraints, of the largest channel used at any location. It is not required that every channel smaller than the span be used in an assignment that attains the span.

Let s be the length of a side of one of the hexagons. We concentrate on the case that there are two levels of interference.

Requirement A: There are several contrainsts on the frequency assignments. First, no two transmitters within distance 4s of each other can be given the same channel. Second, due to spectral spreading, transmitters within distance 2s of each other must not be given the same or adjacent channels: Their channels must differ by at least 2. Under these contraints, what can we say about the span in Figure 1?

Requirement B: Repeat Requirement A, assuming the grid in the example spreads arbitrarily far in all directions.

Requirement C: Repeat Requirements A and B, except assume now more generally that channels for transmitters within distance 2s differ by at least some given integer k, while those at distance at most 4s must still differ by at least one. What cna we say about the span and about efficient strategies for designing assignments, as a function of k?

Requirement D: Consider generalizations of the problem, such as several levels of interference or irregular transmitter placements. What other factors may be important to consider?

Requirement E: Write an article (no more than 2 pages) for the local newspaper explaining your findings.

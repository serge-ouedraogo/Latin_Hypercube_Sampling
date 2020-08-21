#### Latin_Hypercube-Sampling

Latin Hypercube Sampling (LHS)

A latin square is a square grid containing only one sample in each row and in each column. One-dimensional Latin hypercube sampling involves dividing the cumulative density function (cdf) into n equal partitions and then choosing a random data point in each interval.

let’s say for example that we want a random sample of 100 data points from interval [xi, xf]. First, we divide the cdf into 100 equal intervals, then we select the first data from the interval [xi,xf/100]. The second data point would be from the interval [xf/100, 2xf/100], the third from [2xf/100, 3xf/100], and so on. In each interval we would randomly select one point, to obtain 100 different points.

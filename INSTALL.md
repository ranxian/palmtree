### To compile and run the benchmark

#### Install necessary packages

* `sudo apt-get install -y libboost1.54-all-dev libjemalloc1`
* install stx::btree by following https://github.com/bingmann/stx-btree.git

#### Run benchmark

./runbench -t [NUM_THREADS] -c [btree or map] -z [zipf skewness] -u [update ratio] [-i] -k [tree size] -n [num ops]

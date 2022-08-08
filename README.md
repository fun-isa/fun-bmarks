# fun-bmarks
Benchmark programs in Wu


More at: [http://wiki.fun-arch.org/index.php?title=Benchmarking]


## Benchmark coverage

How structured combinators are distributed over benchmark applications, so far? The following image illustrates the occurrence of each combinator type (1 - 64) over a few programs. SK-combinators are shown separately, as a way to compare with traditional abstraction algorithms. 

![Combinator types over benchmark applications.](/eval/coverage.png)

### TODO

As more programs are included in the current test list, we expect to fill more of the gaps of the distribution above. However this is not guaranteed. Our observation is that most Haskell benchmarks from ![nofib](https://github.com/ghc/nofib/) end up using similar data structures and recursion patterns. The result is that these programs tend to cluster around a few reduction patterns.

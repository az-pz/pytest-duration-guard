# pytest-duration-guard
A pytest plugin that tracks each test's wall-clock duration across runs, keeps a noise-tolerant rolling baseline, and flags tests that regress (get slower) or newly appear as slow. Catches slow-creep that pytest-benchmark's microbenchmarks miss. Cross-platform.

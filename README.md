
 ## Tracking functionalities added to the dev branch of fork repository
 * Added Cache level 3 to se.py, caches.py, cacheconfig.py, options.py
 * Resolve fast forward error in Simulation.py - atomic CPU
 * Added way wise read and write latencies for tag and data separtely in cache
 * Custom statistics parameters for cache - "wayhits" - counts way hits per command per way ; "way_hit_counts" - gives overall hit counts per way
 * Added python script for automating simulation with benchmarks
 * New inputs to cache for way specific read and write latencies
 * Support to add odd number of cache ways (--numVictimWays)

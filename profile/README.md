<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cubrid-systems/.github/main/profile/banner-dark.svg">
  <img src="https://raw.githubusercontent.com/cubrid-systems/.github/main/profile/banner-light.svg" alt="CUBRID Systems Research" width="880">
</picture>

CUBRID Systems Research is an independent, experimental R&D effort focused on exploring and improving core technologies of the CUBRID database system.

This is not an official organization, but a space for prototyping, experimentation, and system-level research that may eventually contribute to the CUBRID open-source ecosystem.

The mark above is CUBRID's own tangram, rearranged. Not one piece added, removed
or resized — the same seven that make CUBRID's square, reassembled into a rocket
standing on its pad. The capability is already in CUBRID; what a systems research
group adds is a different arrangement of it. Put the same pieces together another
way and they will fly.

## Current Work

What we are working on, by category:

**Benchmarking**

- [benchbase](https://github.com/cubrid-systems/benchbase) — fork of CMU's BenchBase that adds CUBRID as a JDBC target; fifteen of its eighteen benchmarks run, TPC-C, TPC-H and YCSB among them.
- [HammerDB](https://github.com/cubrid-systems/HammerDB) — fork of HammerDB that adds a CUBRID TPROC-C workload and `cubridtcl`, a Tcl binding over CCI.

**Tooling**

- [cubrid-cluster-sandbox](https://github.com/cubrid-systems/cubrid-cluster-sandbox) — stands a multi-node CUBRID topology up in containers from your own build, and reproduces the states you need a cluster for: replication lag, split brain, failback.
- [cubrid-importdb](https://github.com/cubrid-systems/cubrid-importdb) — one-command reloader for `unloaddb` dumps, built out of tree against the engine it runs with.
- [cubrid-testkit](https://github.com/cubrid-systems/cubrid-testkit) — runs CUBRID's functional tests, taking CTP's tasks over one at a time behind the same commands and the same output.

## Focus Areas

We explore system-level aspects of a relational database system, including:

- Storage and data management
- Query processing and optimization
- Indexing and access methods
- Transaction management and concurrency control
- Logging, recovery, and durability
- System performance and resource management
- Integration with external data systems and tools

## Approach

Our work is driven by practical experimentation:

1. Identify real system problems
2. Build prototypes and test ideas
3. Measure performance and behavior
4. Share results and contribute upstream when appropriate

## Project Types

Work here may take the form of:

- Experimental implementations and prototypes
- Performance experiments and benchmarks
- Integration prototypes and tooling
- Internal tools for analysis and instrumentation

## Philosophy

- Systems-first thinking
- Code over theory
- Measure before optimizing
- Prefer upstream contribution over long-term forks

## Disclaimer

This is an experimental and unofficial effort.  
Projects here may be incomplete, unstable, or subject to change.

---

Exploring and evolving database systems through hands-on research.

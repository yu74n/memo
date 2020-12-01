# Pricipal
1. Define steady state of systems
1. Hypothesize
1. Introduce real-world events
1. Disprove the hypothesize

Experimentation > Testing


Verification > Validation

Chaos Monkey
- vary latency
- change status code

Vary latency is difficult than pegging CPU and filling up RAM
- side car
- SDN
- client-side library wrapper
- service meshes
- lightweight load balancer

Run Experiment in production
- uncover chaos inherent, not cause it.
- If we know undesiable outcome happens, should not run
- critical insight in production may appear first by applying to staging

Automation
- To search numerous condition to possibly contribute to incident
- To catch conditions caused from out side of the scope of our systems
  - change in performance (e.g. network become saturated)
  - change in functionality (e.g. downstream service extra data to take more time to parse)
  - change in human expectation (e.g. original engineers leave...)

Blast Radius

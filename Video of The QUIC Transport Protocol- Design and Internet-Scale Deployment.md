# The QUIC Transport Protocol- Design and Internet-Scale Deployment

Nov. 12, 2019

# Outline

- QUIC design and experimentation 
- Metrics
- Experiences

 # QUIC Design Goals

Deployability and evolvability

Low-latancy secure connection establishment

Stream and multiplexing

Better loss recovery and flexible congestion control

Resilience to NAT-rebinding

# Application Metric

Search Latency

Video Playback Latency

Video Rebuffer Rate

# Why lower Rebuffer Rate?

- Better loss recovery in QUIC

  unique packet number avoids retransmission ambiguity

- TCP receive window limits throughput

  4.6% of connections limited

Both cellular and wireless
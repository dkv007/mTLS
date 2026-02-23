This repository demonstrates how mutual Transport Layer Security (mTLS) can be integrated with an OCPP 1.6 implementation to mitigate integrity‑based attacks, such as Person-in-the-Middle (PiTM), impersonation, and message tampering.
OCPP 1.6 is widely deployed in Electric Vehicle (EV) charging infrastructure, but was designed with minimal built‑in security controls. In many real‑world deployments, authentication is weak or optional, making charging points vulnerable to spoofing and unauthorised access. This project provides:

  A practical, working implementation of mTLS for OCPP 1.6
  A reproducible attack scenario showing how PiTM attacks occur
  An experimental demonstration of how mTLS prevents those attacks

This repository supports the experimental results presented in the associated academic research on securing EV charging infrastructure.

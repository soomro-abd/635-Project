# ECE 635 Project Proposal

## Motivation

Time synchronization is a critical component in cyber-physical systems (CPS), edge computing, and distributed architectures. Many real-world applications—ranging from sensor fusion in autonomous vehicles, to online transactions, and secure credential management—depend on accurate, trusted timing to ensure the integrity and security of system operations. However, modern computing systems face an increasing threat of time-based attacks, where adversaries exploit privileged access to manipulate system clocks, leading to degraded system performance, financial losses, and even physical harm.

In a world where edge systems and CPS play vital roles in critical domains like autonomous vehicles and safety systems, the need for robust and secure time synchronization becomes paramount. Timekeeping inaccuracies can lead to catastrophic failures, such as erroneous decision-making in autonomous systems, failure of safety protocols in critical infrastructure, or even enabling unauthorized access by altering credential expirations.

Although trusted execution environments (TEEs) like Intel SGX, ARM TrustZone, and others provide hardware-based isolation for sensitive data and computations, they have limited capabilities to guarantee the integrity of time services. Additionally, in distributed environments like edge computing, synchronization often relies on external time servers. These servers communicate time information through potentially hostile environments, allowing adversaries to introduce delays, further exacerbating the problem of secure time transfer and synchronization.

**The goal of this project will be to explore a solution that leverages TEEs to solve some of the challenges associated with secure time.**

## Design Goals

## Deliverables

## System Blocks

## HW/SW Requirements

Not known yet.

## Team Members Responsibilities

Solo project.

## Project Timeline

29th September 2024 - Project Proposal Submission

~6th October 2024 - Literature Review and Initial Research

More deadlines to be added after meeting with the professor.

## References

Alder, Fritz, Gianluca Scopelliti, Jo Van Bulck, and Jan Tobias Mühlberg. “About Time: On the Challenges of Temporal Guarantees in Untrusted Environments.” In Proceedings of the 6th Workshop on System Software for Trusted Execution, 27–33. Rome Italy: ACM, 2023. <https://doi.org/10.1145/3578359.3593038>.

Nasrullah, Adeel, and Fatima M Anwar. “Trusted Timing Services with Timeguard.” In 2024 IEEE 30th Real-Time and Embedded Technology and Applications Symposium (RTAS), 1–14. Hong Kong, Hong Kong: IEEE, 2024. <https://doi.org/10.1109/RTAS61025.2024.00009>.

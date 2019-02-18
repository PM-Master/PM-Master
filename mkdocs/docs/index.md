# Introduction

The Policy Machine is an ever evolving reference implementation of the Next Generation Access Control (NGAC) standard.
It started as a standalone Java program called Harmonia and has started it's next evolution to bring the NAGC standard 
to web based application through an administrative REST API. The goal of the Policy Machine is to demonstrate 
the power of NGAC and the benefits it can bring to the security industry. 

The Policy Machine projects currently being supported are:

- [Policy Machine Core](/policy-machine-core) - The core functionality behind the Policy Machine is the NGAC graph and the algorithms used to query the access state 
    of a graph. The Policy Machine Core project provides these components as a Java library and can easily be imported 
    into any project using maven.
    
- [Policy Machine](/policy-machine) (WIP) - The Policy Machine is our current environment for testing and demonstrating NGAC features.  It incorporates every 
    component of the NGAC functional architecture: Policy Enforcement Point (PEP), Policy Decision Point (PDP), Policy
    Information Point (PIP), Policy Access Point (PAP), and Event Processing Point (EPP).  
     
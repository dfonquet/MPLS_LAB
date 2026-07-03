
# MPLS_LAB

This repository contains a set of practical configurations based on a **small-scale Service Provider / ISP network design**.

The purpose of this lab is to practice and document core **MPLS, routing, VPN, and traffic engineering concepts** commonly used in Service Provider environments.

---

## 🔧 Lab Scope

<details>
<summary><strong>MPLS on Provider Edge Devices</strong></summary>

MPLS is enabled across Provider Edge devices to support label switching, VPN services, and Service Provider transport use cases.

</details>

<details>
<summary><strong>OSPF as Core Routing Protocol</strong></summary>

OSPF is used as an underlay routing protocol to provide IP reachability across the MPLS backbone.

</details>

<details>
<summary><strong>IS-IS Core Routing</strong></summary>

IS-IS is used as an alternative Service Provider underlay protocol for scalable core routing and MPLS transport.

</details>

<details>
<summary><strong>MP-BGP and iBGP Templates</strong></summary>

MP-BGP and iBGP templates are used to simplify peer configuration and support scalable VPN route exchange.

</details>

<details>
<summary><strong>Route Reflector Design</strong></summary>

Route Reflectors are implemented to reduce full-mesh iBGP requirements and improve control-plane scalability.

</details>

<details>
<summary><strong>VRF Implementation</strong></summary>

Virtual Routing and Forwarding instances are configured to provide routing separation between customer networks.

</details>

<details>
<summary><strong>MPLS Layer 3 VPN</strong></summary>

L3VPN services are implemented using VRFs, Route Distinguishers, Route Targets, and MP-BGP VPNv4/VPNv6 control-plane concepts.

</details>

<details>
<summary><strong>MPLS Layer 2 VPN</strong></summary>

L2VPN services are implemented to provide point-to-point or multipoint Layer 2 transport across the MPLS backbone.

</details>

<details>
<summary><strong>Traffic Engineering</strong></summary>

Traffic Engineering is explored to influence path selection, optimize backbone resources, and improve network resiliency.

</details>

<details>
<summary><strong>Prefix Filtering and Routing Policy</strong></summary>

Routing policies and prefix filtering are used to control route advertisement, protect the control plane, and improve routing hygiene.

</details>

<details>
<summary><strong>EIGRP Customer Edge Integration</strong></summary>

EIGRP is used in selected customer-facing scenarios to practice PE-CE routing integration and route redistribution.

</details>

---

## 🎯 Lab Objectives

* Build a functional MPLS-based Service Provider topology.
* Practice MPLS, VRF, L3VPN, L2VPN, and MP-BGP concepts.
* Understand the interaction between IGP, MPLS, and BGP control planes.
* Explore routing policy, prefix filtering, and route redistribution.
* Validate Service Provider design principles in a controlled lab environment.
* Document configurations for future study, troubleshooting, and improvement.

---

## 🧠 Notes

This lab is part of my continuous learning process in **Service Provider networking, MPLS, routing architecture, and network design**.

It is not intended to represent a production-ready ISP deployment, but rather a structured technical lab for learning, testing, and improving real-world networking skills.

---

## 📬 Feedback

Thank you for taking the time to explore this repository.

Feedback, suggestions, and technical discussions are always welcome. If you have any questions or comments, feel free to reach out.

Have a great day!

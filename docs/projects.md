## Our Contribution to Official Honeynet Projects

Our chapter actively contributes to the following official Honeynet Project tools:

### [Glutton](https://github.com/mushorg/glutton)

**Status**: Active Global Honeynet Project  
**Chapter Lead**: Muhammad Bilal Arif  

Glutton is a protocol-agnostic honeypot designed to emulate various network services and protocols. It captures malicious network activity by intercepting connections via iptables/TPROXY and logging interaction data. 

#### Our Contributions
- Original development of Glutton as a versatile, multi-protocol honeypot
- Implementation of the core honeypot functionality in Go programming language
- Ongoing maintenance and feature development to enhance protocol support

#### GSoC Involvement
Our Chapter Lead is currently mentoring for this project as part of Google Summer of Code 2025. The GSoC project focuses on enhancing Glutton with Spicy integration to improve protocol parsing capabilities.

- **Project Goal**: Develop a Go wrapper to integrate Spicy with Glutton and implement protocol parsers for HTTP and DNS
- **Expected Outcomes**: 
  - A functional Go wrapper for Spicy integration
  - Working HTTP and DNS protocol parsers
  - Comprehensive documentation for future protocol implementations
  - Enhanced capability to capture and analyze protocol-specific attack patterns
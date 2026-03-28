# Assignment: Paper Relationship Presentation

## Description
This assignment analyzes the relationship between two research papers in maritime cybersecurity, focusing on honeynets and cyber deception.

## Selected Papers

1. Pijpker, J., & McCombie, S. (2023)  
   "A Ship Honeynet to Gather Cyber Threat Intelligence for the Maritime Sector"

2. Brouwer, S., Pijpker, J., & Mohsen, F. (2025)  
   "HoneyShip: Unveiling Cyber Threats to Maritime VSAT Systems with a High-Interaction Honeypot"

## Relationship Summary

The 2023 paper introduces the concept of a ship-based honeynet to collect cyber threat intelligence in maritime environments. It provides a foundational design and highlights the importance of realistic simulation for studying attacker behavior.

The HoneyShip paper builds directly on this work by implementing a high-interaction honeypot specifically targeting maritime VSAT systems. It adopts design recommendations from earlier work, such as realistic system behavior and network characteristics, and enhances them by integrating real-world vulnerabilities, real-time ship data, and advanced monitoring tools.

Unlike the earlier conceptual approach, HoneyShip provides a fully deployed system that collected over 39,000 interactions from real attackers. This demonstrates a clear progression from theoretical design to practical implementation.

Thus, the second paper cites the first because it provides the foundational framework, which is then extended into a more realistic, specialized, and data-driven honeynet system.

## Files
- README.md
- presentation (Google Slides)

## BibTeX Entries

```bibtex
@inproceedings{pijpker2023ship,
  author={Pijpker, Jeroen and McCombie, Stephen},
  title={A Ship Honeynet to Gather Cyber Threat Intelligence for the Maritime Sector},
  booktitle={IEEE Conference},
  year={2023}
}

@inproceedings{brouwer2025honeyship,
  author={Brouwer, Stern and Pijpker, Jeroen and Mohsen, Fadi},
  title={HoneyShip: Unveiling Cyber Threats to Maritime {VSAT} Systems with a High-Interaction Honeypot},
  booktitle={IEEE International Conference on Industrial Cyber-Physical Systems},
  year={2025}
}

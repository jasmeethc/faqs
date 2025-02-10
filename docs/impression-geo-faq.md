
---
title: FAQ - Understanding Geo-Discrepancies in Ad Reporting
description: Learn why geo-location reports differ across ad platforms and how to interpret them accurately.
---

## 1. Why do geo-location reports differ between our ad server and client platforms like DV360, DFP, etc.?
Geo-location data is determined using IP-based databases, and different platforms use different vendors or methodologies to map IP addresses to locations. Our ad server relies on MaxMind, while platforms like DV360 and DFP may use different providers, leading to minor discrepancies.

## 2. What factors contribute to geo-reporting mismatches?
Several factors impact geo-reporting differences:
- **IP Database Variations**: Different providers update their databases at different intervals, leading to variations in mappings.
- **IP Reassignment**: Internet Service Providers (ISPs) frequently change or reassign IPs, which may not be reflected in real-time across all databases.
- **VPNs and Proxies**: Users accessing content via VPNs, proxies, or mobile networks may appear in different locations.
- **Mobile Carrier IP Pools**: Mobile network users often share IPs that may be assigned to a broader region rather than a precise city.
- **Different Measurement Methodologies**: Each ad platform may apply different confidence levels or methodologies in determining location accuracy.

## 3. What are the expected levels of discrepancy?
Based on industry norms and our observations, geo-reporting discrepancies typically fall within the following ranges:
- **City-level mismatches**: Up to 20%
- **State/Region-level mismatches**: Up to 10%
- **Country-level mismatches**: Typically within 2%

## 4. Why are city-level discrepancies higher than state or country-level?
City-level location accuracy depends on precise IP-to-location mapping, which is more prone to inaccuracies due to:
- Frequent IP reassignments within a region
- Users connecting through ISPs with data centers in neighboring cities
- Edge cases where city boundaries are not clearly defined in the IP database

State and country-level reporting is generally more stable, but minor variances can still occur due to regional ISP routing practices.

## 5. Can geo-reporting be made 100% accurate?
No, due to the nature of IP-based geo-location, 100% accuracy is not possible. However, we continuously update and refine our database to minimize discrepancies.

## 6. How can clients interpret geo-location data more effectively?
We recommend clients:
- Use trends and patterns rather than absolute numbers for geo analysis
- Cross-check data over time to identify consistent patterns rather than single-day snapshots
- Consider alternative verification methods like user registration data or survey-based geo-validation when high accuracy is required

## 7. Who should clients contact for further clarification?
For any concerns regarding geo-discrepancies, clients can reach out to our support team for detailed analysis and insights.

By understanding these expected variations, clients can better interpret their geo-reports and make informed decisions. If you need further clarification, feel free to contact our support team!

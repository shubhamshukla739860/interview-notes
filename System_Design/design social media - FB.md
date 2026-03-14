
# scan all online resources leetcode discussion linkedin post and all other plateform like google query search quara search and give me list of system design questions asked in walmart system design round

Here’s a consolidated list of system‑design style questions that are explicitly reported as being asked in Walmart / Walmart Global Tech interviews, plus the Walmart‑specific variants that prep sites call out as “common Walmart system design questions.” I’ve de‑duplicated overlapping items and grouped them by theme.

***

## A. Reported “exact” Walmart system design questions

These come from LinkedIn posts and interview write‑ups that explicitly say they were asked at Walmart.[^1][^2][^3][^4][^5][^6]

**General product / social systems**

- Design Twitter.[^3][^6]
- Design the Feeds section of Instagram / Facebook.[^2]
- Design Google Play Store.[^6][^3]

**Retail / e‑commerce \& Walmart‑like flows**

- Design an e‑commerce platform.[^4][^3][^6]
- Design an order management system.[^3][^6]
- Design a recommendation system / “Frequently Bought Together” recommendations system.[^5][^4][^6][^3]
- Design a real‑time inventory tracking system.[^4][^6][^3]
- Design a rating system for an e‑commerce website (Flipkart/Walmart‑like).[^1][^6][^3]
- Design a warehouse management system.[^6][^3][^4]

**Infrastructure / platform components**

- Design a load balancer.[^3][^4][^6]
- Design a URL shortener.[^6][^3]
- Design a logging system.[^3][^6]

**Mobility / domain‑specific apps**

- Design Aarogya Setu.[^6][^3]
- Design Zoomcar app (LLD).[^3][^6]
- Design an app for waste management.[^6][^3]
- Design a reservation system for a parking lot.[^3][^6]

**Classic LLD questions sometimes paired with Walmart**

- Design a library management system (LLD).[^6][^3]
- Flash‑sale / high‑concurrency purchase service (design + code, LLD+HLD style).[^5]

***

## B. Walmart‑domain questions from focused guides

Several dedicated Walmart system‑design prep guides list common Walmart‑style questions that map directly to real retail systems (inventory, payments, logistics, etc.).[^7][^8][^9][^10][^4]

**Walmart marketplace and checkout**

- How would you design Walmart’s online marketplace (buyers, sellers, catalog, orders, payments, notifications)?[^8]
- Design Walmart’s payment and settlement system / payment processing pipeline.[^8]
- Design the checkout and order‑fulfillment flow for Walmart’s online store (pricing, cart, promotions, payment, order status).[^10]

**Inventory, logistics, and fulfillment**

- Design a global / real‑time inventory management system across stores, warehouses, and online orders.[^7][^10][^8]
- Design a warehouse management system (receiving, put‑away, picking, packing, shipping).[^10][^4]
- Design an order fulfillment and delivery system (routing from fulfillment centers / stores to customers, last‑mile logistics).[^7][^10]
- Design a multichannel curbside‑pickup and store‑assignment system.[^10]

**Search, discovery, and personalization**

- Design Walmart’s product search and discovery system (indexing billions of SKUs, autocomplete, relevance, typo‑tolerance).[^8][^10]
- Design Walmart’s product recommendation system (personalized, real‑time, at scale).[^4][^8][^10]
- Design a “Frequently Bought Together” recommendation pipeline over historical purchase data.[^5][^8]

**Fraud, risk, and trust**

- Design a fraud detection system for Walmart transactions.[^8][^10]
- Design a trust/safety system that flags suspicious orders or accounts in real time.[^10][^8]

**Notifications, reliability, and resilience**

- Design a notification system for order updates (email/SMS/push, retries, dead‑letter handling).[^8]
- How would you ensure Walmart remains operational if a regional data center goes down? (multi‑region, active‑active, failover).[^8]

**IoT / in‑store systems**

- Design real‑time in‑store IoT monitoring (shelf sensors, POS terminals) that works even when stores are offline and syncs later.[^7][^10]

***

## C. How to use this list

- Items in section **A** are the closest to “verbatim questions” reported by specific candidates and coaching pages claiming “EXACT questions asked at Walmart in 2025.”[^2][^1][^5][^3][^6]
- Items in section **B** are from Walmart‑specific system design guides that aggregate “common Walmart questions” around inventory, checkout, logistics, payments, fraud, and recommendations, and are very representative of what interviewers like to ask.[^9][^4][^7][^10][^8]

If you tell me which role level you’re targeting (SDE‑2 vs SDE‑3) and whether your team is more e‑commerce, supply‑chain, or platform, I can pick 5–7 of these that are most likely for you and outline exactly how to approach each in an interview.
<span style="display:none">[^11][^12][^13][^14][^15][^16][^17][^18][^19][^20][^21][^22][^23][^24][^25][^26][^27]</span>

<div align="center">⁂</div>

[^1]: https://www.youtube.com/watch?v=tCZ-oc6A3bk

[^2]: https://www.linkedin.com/posts/shivam-99-somani_walmart-interview-experience-round-activity-7389553074761031680-odQ7

[^3]: https://www.linkedin.com/posts/rajatgajbhiye_walmart-system-design-interview-questions-activity-7305588439654043648-fklS

[^4]: https://www.geeksforgeeks.org/interview-experiences/walmart-interview-questions-for-technical-profiles/

[^5]: https://www.linkedin.com/posts/arun-25_interview-leetcode-walmart-activity-7379367629930627073-uWXJ

[^6]: https://www.linkedin.com/posts/interview-stop_systemdesign-walmartinterview-campusplacements-activity-7358493238690816000-FgEj

[^7]: https://www.codinginterview.com/guide/walmart-system-design-interview-questions/

[^8]: https://www.systemdesignhandbook.com/guides/walmart-system-design-interview/

[^9]: https://www.tryexponent.com/blog/walmart-interview-process

[^10]: https://www.educative.io/blog/walmart-system-design-interview-questions

[^11]: https://www.geeksforgeeks.org/interview-experiences/walmart-interview-experience-for-sde3/

[^12]: https://www.interviewquery.com/interview-guides/walmart-software-engineer

[^13]: https://leetcode.com/discuss/interview-question/6146141/Walmart-SSE-Interview-Experience-or-DSA-or-LLD/

[^14]: https://www.youtube.com/watch?v=sPSiCMTzqC0

[^15]: https://www.reddit.com/r/csMajors/comments/114qo61/does_walmart_global_tech_ask_system_design/

[^16]: https://www.tryexponent.com/questions?company=walmart-labs\&role=em\&type=system-design

[^17]: https://javascript.plainenglish.io/interview-experience-at-walmart-global-tech-for-swe-iii-position-119aeccd36a1

[^18]: https://gist.github.com/Neilblaze/fb87b8d1be275df1a1b83d0e58d14123

[^19]: https://expertbeacon.com/designing-at-scale-how-walmart-created-a-design-system-for-2-million-associates/

[^20]: https://www.linkedin.com/posts/rajatgajbhiye_during-my-system-design-round-at-walmart-activity-7400390566359851008-rkBO

[^21]: https://www.reddit.com/r/leetcode/comments/1fhsa6x/walmart_global_tech_system_design_questions/

[^22]: https://www.codinginterview.com/guide/walmart-interview/

[^23]: https://dev.to/kriti_pare/interview-experience-at-walmart-global-tech-for-swe-iii-position-k95

[^24]: https://www.interviewquery.com/interview-guides/walmart-data-engineer

[^25]: https://code.likeagirl.io/my-walmart-interview-experience-9cfec6c801a

[^26]: https://www.linkedin.com/posts/ramakanthd92_amazon-walmart-adobe-activity-7337069585222746112-RWrR

[^27]: https://www.datainterview.com/blog/walmart-data-engineer-interview


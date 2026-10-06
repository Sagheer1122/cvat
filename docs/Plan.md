Plan - Annotation Analytics

Target Scope
Main 8 hours ke limit mein items 1 se 5 deliver kar raha hoon:
1. CVAT setup aur COCO data verify karna.
2. Nayi Django app "test" mein annotation count API banana.
3. Auth aur permissions handle karna (401 aur 403 cases).
4. Task page par graph banana, sath mein empty aur error states.
5. 5 runs ke sath API response time measure karna.
6. Under 5 minutes ki Loom recording complete karna.

Items 8 aur 9 (WebSocket aur reconnect) scope se bahar rakhe hain taake core requirement solid bane.

Time Estimates
- Setup aur Data Check: 45 mins
- Backend App aur Query: 2 hours
- Frontend Graph UI: 2 hours
- Benchmarks aur Docs: 1 hour
- Loom Recording: 45 mins

Decision Record
- Chosen Approach: Django ORM DB aggregation use ki hai.
- Rejected Approach: Shapes ko memory mein load karke Python mein count karna.
- Trade-off: ORM query likhne ke liye structure samajhna pada, lekin is se memory leak aur crash nahi hoga.
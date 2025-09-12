# Page Search

### Observation:

1. The same concept in [workflowtype-search.md](workflowtype-search.md "mention") can benefit Scott in the 'Pages' Page.



### Solution:

1. I created a new **Page Parameter Filter** Block [BlockId: 13834]
   - You can search by Page Internal Name, Site Name, or Id
2. I updated the old search Block [BlockId: 8388]
   - It used to show two anchor tags that each link to a child Page [PageIds: 3466, 3884]
   - Now, it only shows one anchor tag: the one that navigates to Page Views
   - I also deleted the "search results" Page, it was named "Page Search" [PageId: 3466]

<figure><img src="../.gitbook/assets/Screenshot 2025-09-12 at 12.11.21 PM.png" alt=""><figcaption></figcaption></figure>

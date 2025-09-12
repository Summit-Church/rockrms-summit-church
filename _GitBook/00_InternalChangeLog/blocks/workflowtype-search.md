# WorkflowType Search

### Observation:

1. If I want to search for "Landing Page", the current search box navigates me to a separate page.
2. If I want to search for WorkflowTypeId, the current search box does not offer that functionality.
3. If I want to search for WorkflowType's Category name, I cannot do that either.

<div align="left"><figure><img src="../.gitbook/assets/Screenshot 2025-09-12 at 11.05.06 AM.png" alt=""><figcaption></figcaption></figure></div>

### Solution:

1. I created a new \<u>Page Parameter Filter\</u> Block.
   1. You can search by WorkflowType Name, Category, or Id
2. I deleted the old search Block.

<figure><img src="../.gitbook/assets/recording.gif" alt=""><figcaption></figcaption></figure>

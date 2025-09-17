# WorkflowType Overview

### Observation:

1. When I'm navigating the WorkflowTypes page, and I select a Category, I would like to have an overview of WorkflowTypes that are within that Category



### Solution:

1. I added a **Dynamic Data** Block that queries the `CategoryId` in the URL and shows some of the WorkflowType Properties of the WorkflowTypes within that Category.

<figure><img src="../.gitbook/assets/Screenshot 2025-09-17 at 4.09.24 PM.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2025-09-17 at 4.13.35 PM.png" alt=""><figcaption></figcaption></figure>



### Bonus:

This might affect the page load time, but if you add `ShowMostRecent=1` among the URL Parameters, there will be a new column that shows the most-recent Workflow instance for each WorkflowType.

<figure><img src="../.gitbook/assets/Screenshot 2025-09-17 at 4.18.35 PM.png" alt=""><figcaption></figcaption></figure>

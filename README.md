<h1>Resource tags and locks</h1>

<h2>Description</h2>
This lab will configure resource tags and locks.<br /><br />

Azure resource tags are key-value pairs that you can assign to Azure resources to help organize and manage them. Tags can be used for various purposes, including:

<b>Organization:</b> Group resources by projects, departments, environments (e.g., production, staging), or other criteria.<br />
<b>Cost Management:</b> Track costs and usage based on tags, which can help in budgeting and chargeback scenarios.<br />
<b>Automation:</b> Use tags in automation scripts and policies to manage resources more effectively.<br />
<b>Governance:</b> Enforce policies and compliance by tagging resources appropriately.<br /><br /><br />


Azure resource locks are a feature that helps you protect your Azure resources from accidental deletion or modification. By applying locks, you can ensure that critical resources remain intact and are not altered without proper authorization. There are two types of locks in Azure:

Types of Locks<br />
<b>Read-Only Lock:</b>
When applied, this lock prevents any modifications to the resource. Users can still read the resource, but they cannot delete or change it.
Useful for protecting critical resources that should not be altered.

<b>Delete Lock:</b>
This lock prevents the resource from being deleted. However, users can still read and modify the resource.
Ideal for ensuring that resources cannot be removed accidentally.



<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Lab walk-through:</h2>

<p align="center">

<h4>Step 1</h4> 
Assigning resource tags.<br/>
<img src="https://i.imgur.com/l1QkASa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<h4>Step 2</h4> 
Assigning resource locks.<br/>
<img src="https://i.imgur.com/IYRwCWg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



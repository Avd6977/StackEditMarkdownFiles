---


---

<h2 id="hcms-items">HCMS Items</h2>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Pending Items Changes
<ul>
<li>Added categories and tags to pending items, disable save until form is dirty</li>
<li><a href="https://kraken.civicplus.com/app/alex/content/article/53cc1266-8583-4e71-aabb-e5139331def5">https://kraken.civicplus.com/app/alex/content/article/53cc1266-8583-4e71-aabb-e5139331def5</a></li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Upgrade Borealis Core to dotnet core 2.1
<ul>
<li>Discuss</li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Allow webhooks for submitted/declined assets
<ul>
<li><a href="https://kraken.civicplus.com/app/alex/rules">https://kraken.civicplus.com/app/alex/rules</a></li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> No server side validation for put
<ul>
<li>There was, but required fields on Squidex BE are defaulted to allow empty strings. Changed to disallow this</li>
<li>Patch had a small change to merge in data</li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled="">  Remove default Froala links (Froala, Facebook, Google)
<ul>
<li><a href="https://kraken.civicplus.com/app/alex/content/article/53cc1266-8583-4e71-aabb-e5139331def5">https://kraken.civicplus.com/app/alex/content/article/53cc1266-8583-4e71-aabb-e5139331def5</a></li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Fix initial scheduler implementation
<ul>
<li>The scheduler was broken on Squidex, but also had some changes to make it work with Elastic</li>
<li>On Assets and Content for publish and unpublish only</li>
<li><a href="https://kraken.civicplus.com/app/alex/assets">https://kraken.civicplus.com/app/alex/assets</a></li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Expire at the end of day
<ul>
<li>If archiving or unpublishing, set the schedule to EOD unless otherwise specified</li>
<li><a href="https://kraken.civicplus.com/app/alex/assets">https://kraken.civicplus.com/app/alex/assets</a></li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Disable fields for authors when needed
<ul>
<li>A lot of fields weren’t disabled when they should be for authors</li>
<li>Couldn’t save anyway, no button, but makes it appear you could</li>
<li>Had to hide the markdown toolbar, SimpleMDE doesn’t have a dynamic disable capability, but there is a PR someone made for it</li>
<li><a href="https://kraken.civicplus.com/app/alex/content/article">https://kraken.civicplus.com/app/alex/content/article</a></li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Add filter for apps and to update categories call to use OData
<ul>
<li>Apps and categories now have paging, searching, etc that comes with OData</li>
<li><a href="https://kraken.civicplus.com/app/alex/settings/categories">https://kraken.civicplus.com/app/alex/settings/categories</a></li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Bulk Assign Categories to Items
<ul>
<li>From assets, implemented the same for content</li>
<li><a href="https://kraken.civicplus.com/app/alex/content/article">https://kraken.civicplus.com/app/alex/content/article</a></li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Limit Guests to Read Only End Points
<ul>
<li>Matt to discuss a lot of what was done</li>
<li>Restricted methods with side effects to authorized CivicEngage users</li>
<li>Implemented IdentityServer token</li>
</ul>
</li>
</ul>
<h2 id="civicengage-6-items">CivicEngage 6 Items</h2>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Update Type of Content Filter
<ul>
<li>Customer request, we needed to update the way this worked because it was confusing</li>
<li><a href="https://borealis.civicplus.com/">https://borealis.civicplus.com/</a></li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Sort By Date
<ul>
<li>Upcoming became Date - Ascending</li>
<li>Default to remove past dates with a checkbox</li>
<li><a href="https://borealis.civicplus.com/">https://borealis.civicplus.com/</a></li>
</ul>
</li>
</ul>


---

copyright:
  years: 2017
lastupdated: "2017-09-27"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}

# Purging Cached Content for a Storage CDN Account

<table class="wrapped">
        <colgroup>
          <col/>
        </colgroup>
        <tbody>
          <tr>
            <th>This documentation refers to a legacy offering. To learn about our new CDN solution please read on <a href="https://console.bluemix.net/docs/infrastructure/CDN/about.html#about-cdn">here</a>.</th>
          </tr>
        </tbody>
</table>

Outdated content for a CDN Account may be purged manually from all Points of Presence (POPs) so that updated content may be propagated for view when content is next requested. Upon requesting a purge, content is removed from all POPs and must be manually propagated for a content update. Purges take approximately 3-5 minutes to complete. Follow the steps below to purge content from the CDN.

## Purge Cached Content

1. Access the CDN interface. Refer to [Access the CDN Screen](access-cdn-screen.html).
2. Click the **Account ID** for the desired CDN Account to access the account.
3. Click the **Cache Management** tab.
4. Enter up to 15 URLs in the **Content URL(s)** field.
5. Click the **Purge** button to purge cached content from the specified URL(s).

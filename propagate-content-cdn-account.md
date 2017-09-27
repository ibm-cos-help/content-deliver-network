---

copyright:
  years: 2017
lastupdated: "2017-09-27"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}

# Propagate Content for a Storage CDN Account

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

New and updated content may be propagated to all Points of Presence (POPs) for your CDN Account manually. Upon requesting propagation, the content is immediately pulled from its origin and pushed to all POPs so that it is available when it is next requested by a client. Propagation takes 10-15 minutes to complete. Follow the steps below to propagate content for a CDN Account.

## Propagate Content

1. Access the **CDN** interface. Refer to [Access the CDN Screen](access-cdn-screen.html).
2. Click the **Account ID** for the desired CDN Account to access the account.
3. Click the **Cache Management** button.
4. Enter up to five (5) URLs in the **Content URL(s)** field.
5. Click the **Propagate** button to propagate new or updated content to the specified URL(s).

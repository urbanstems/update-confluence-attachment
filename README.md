# Update Attachment On A Page In Confluence

Self-explanatory!
Based heavily on https://github.com/Bhacaz/docs-as-code-confluence

## Parameters

| Name                  | Description                                                                                                                                                                                              | Required |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| `username`            | Confluence username or email                                                                                                                                                                             | true     |
| `password`            | Confluence password or [API token](https://support.atlassian.com/atlassian-account/docs/manage-api-tokens-for-your-atlassian-account/)                                                                   | true     |
| `confluence-base-url` | Your Confluence URL (with `wiki`). Example: `https://mydomain.atlassian.net/wiki`                                                                                                                        | true     |
| `space-id`            | Confluence **space key** to publish the documentation. Located after `spaces` in the URL. `https://mydomain.atlassian.net/wiki/spaces/<<~1234>>`. <br> Or in _Space settings_ > _Space details_ > _Key_. | true     |
| `parent-page-id`      | Page id under which the documentation will be published. Located after `pages` in the URL. `https://mydomain.atlassian.net/wiki/spaces/~1234/pages/<<1234>>/My+Parent+Page`                              | true     |

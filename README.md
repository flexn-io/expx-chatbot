
# expx-chatbot

Public CDN mirror of the chat-bubble widget. Bundle is auto-published from
[`flexn-io/prd-asilab-skunkworks`](https://github.com/flexn-io/prd-asilab-skunkworks)
(`packages/host-expx-chatbot`). Don't edit this repo by hand.

## Embed it

```html
<script src="https://cdn.jsdelivr.net/gh/flexn-io/expx-chatbot@main/expx-chatbot.iife.js" defer></script>
<script>
    window.addEventListener('load', () => {
        window.ExpxChatbot.mount({
            apiUrl: 'https://your-asilab-host.example.com',
            hostlinkPath: 'mission-control',
            neuraflowId: '<active-neuraflow-id>',
            blueprintId: 'universal',
            user: { userId: '<user-id>', fullName: 'Jane Operator' },
        });
    });
</script>
```

Swap `@main` for `@vX.Y.Z` to pin to a release.

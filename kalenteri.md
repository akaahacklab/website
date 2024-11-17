---
permalink: /kalenteri/
---

<iframe id="nc_calendar_embed" width="100%" height="1000" src="https://nc.akaa.hacklab.fi/apps/calendar/embed/6MQ2TQWx7tqrk9cj/listMonth/now"></iframe>

<script type="text/javascript">
    function adjustIframeHeight() {
        const iframe = document.getElementById('nc_calendar_embed');

        iframe.onload = function () {
            // Ensure we can access the iframe's content
            if (iframe.contentDocument && iframe.contentDocument.body) {
                iframe.style.height = iframe.contentDocument.body.scrollHeight + 'px';
            } else if (iframe.contentWindow && iframe.contentWindow.document) {
                iframe.style.height = iframe.contentWindow.document.body.scrollHeight + 'px';
            }
        };
    }

    adjustIframeHeight();
</script>

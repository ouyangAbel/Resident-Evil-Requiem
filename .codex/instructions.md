# Project Instructions

## Google Analytics Tracking Code

Every HTML page created for this project MUST include the following Google Analytics tracking code immediately after the `<head>` tag:

```
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GF9BYLZ5F7"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GF9BYLZ5F7');
</script>
```

This is required for all new HTML files and pages generated for the Resident Evil Requiem game website.

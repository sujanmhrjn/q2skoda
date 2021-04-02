1.Update / ADD /Remove relevant meta tags from AMP page refereing to non-AMP page e.g
  1.1. Title
  1.2. Description
  1.3. og:url
  1.4. og:title
  1.5. og:description
  1.6. og:image
2.Update schema.org attributes on AMP page with relevant content from non-AMP page
  <script type="application/ld+json">
        {
          "@context": "http://schema.org",
          "@type": "NewsArticle",
          "headline": "",
          "datePublished": "",
          "image": [
            "
          ]
        }
  </script>
2.Upload the package received on the server with any of the following options that best fits you needs:
  a. sub-domain
  b. inside a sub-folder
  c. as a new page on existing CMS 
3.The outcome of the step 1 should be a unique url for AMP page.

4.Link non-AMP and AMP 
  4.1. Add the following meta tag to the non-AMP page (original page): page (if not present)
    <link rel="amphtml" href="url to the AMP page">
  4.2. And the folowing to the AMP page:
    <link rel="canonical" href="urk to your non-amp page">

Ref:
1. https://amp.dev/documentation/guides-and-tutorials/start/create/prepare_for_discovery/?format=websites
2. https://amp.dev/documentation/guides-and-tutorials/start/create/basic_markup/?format=websites


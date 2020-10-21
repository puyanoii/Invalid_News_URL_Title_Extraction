# URL_Title_Extraction
This script can be used to extract titles from invalid news URLs

There are two commen pattern in invalid URLs that contain information about the title of the article:
1. Keywords apprear AFTER the last / in the path of the URL
2. Keywords of titles are connected by "-"

We use urllib.parse and regex to extract keywords of titles from the URLs

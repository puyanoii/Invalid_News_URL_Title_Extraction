# URL_Title_Extraction
This script can be used to extract titles from invalid news URLs

There are two commen pattern in invalid URLs that contain information about the title of the article:
1. Keywords apprear AFTER the last / in the path of the URL
2. Keywords of titles are connected by "-"

An example of invalid URL: https://www.dailyconservative.com/poll-do-you-stand-with-sarah-sanders?fbclid=IwAR3Wdwducv0S4TAaDHL7ROG7ZemVsdcMLxCJGNb63OElIBUQ9e7kTQdCthI 

Title should be: "pool do you stand with sarah sanders" in the article

We use urllib.parse and regex to extract keywords of titles from the URLs

# Instructions for downloading X12 claim files from CollaborateMD
## Preparation
Drag this link to your bookmarks bar: [Download X12](javascript:(function()%7Blet%20a%20%3D%20document.createElement(%22a%22)%3B%0Aa.href%20%3D%20URL.createObjectURL(new%20Blob(%5B...document.querySelectorAll('.ansi-line')%5D.map(el%20%3D%3E%20el.innerText)))%3B%0Aa.download%20%3D%20'cmd_'%20%2B%20document.URL.split(%22%2F%22).at(-1)%20%2B%20'_'%20%2B%20(new%20Date).toISOString().substring(0%2C%2010)%20%2B%20'.x12'%3B%0Adocument.body.appendChild(a)%3B%0Aa.click()%3B%0AsetTimeout(()%3D%3E%7B%20document.body.removeChild(a)%3B%20URL.revokeObjectURL(a.href)%20%7D%2C%200)%3B%7D)()%3B)
## For each claim
1. Follow [these instructions](https://help.collaboratemd.com/help/preview-electronic-claim) to view the claim file preview
2. Click the bookmark you added earlier, and the file will download automatically

# code-to-convert-e-send-files-to-client

```
 const { data } = await getDocumentToImportLeads(values.salePointId)
    const url = window.URL.createObjectURL(new Blob([data]))
    const link = document.createElement('a')
    link.href = url
    link.setAttribute('download', 'import-leads.xlsx')
    document.body.appendChild(link)
    link.click()
```

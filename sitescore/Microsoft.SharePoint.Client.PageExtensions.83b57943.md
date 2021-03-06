# PageExtensions.AddWebPartToWikiPage Method  
 Add web part to a wiki style page   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static WebPartDefinition AddWebPartToWikiPage(this Web web, String serverRelativePageUrl, WebPartEntity webPart, Int32 row, Int32 col, Boolean addSpace)
```
### Parameters
#### web  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Site to be processed - can be root web or sub site  

  

#### serverRelativePageUrl  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Server relative url of the page to add the webpart to  

  

#### webPart  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Entities.WebPartEntity](OfficeDevPnP.Core.Entities.WebPartEntity.md)  
&emsp;&emsp;Information about the web part to insert  

  

#### row  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;Row of the wiki table that should hold the inserted web part  

  

#### col  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;Column of the wiki table that should hold the inserted web part  

  

#### addSpace  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;Does a blank line need to be added after the web part (to space web parts)  

  

### Return Value
Type: WebPartDefinition  
Returns the added Microsoft.SharePoint.Client.WebParts.WebPartDefinition object  


## See also
- [PageExtensions](Microsoft.SharePoint.Client.PageExtensions.md) 
- Microsoft.SharePoint.Client.WebParts.WebPartDefinition
- System.ArgumentException
- System.ArgumentNullException
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 

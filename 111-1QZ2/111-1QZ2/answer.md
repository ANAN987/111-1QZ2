# 第2次隨堂-隨堂-QZ2
>
>學號：109111116
><br />
>姓名：朱羿安
><br />
>作業撰寫時間：40 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/10/26
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容


下段程式碼則為使用後結果：

```csharp
namespace _111_1QZ2
{
    public partial class Test : System.Web.UI.Page
    {
        protected void Page_Load(object sender, EventArgs e)
        {
            lb_Msg.Text = "Page_Load";
        }

        protected System.Void btn_Submit_Click(System.Object sender, System.EventArgs e)
        {
            lb_Msg.Text = "btn_Event";
        }
    }
}
}
```


下段程式碼則為使用後結果：

```html
<%@ Page Language="C#" AutoEventWireup="true" CodeBehind="Test.aspx.cs" Inherits="_111_1QZ2.Test" %>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
            <asp:Label ID="lb_Msg" runat="server"></asp:Label>
            <asp:Button ID="btn_Submit" runat="server" Text="送出" Height="40px" Width="40px" OnClientClick="btn_Submit" OnClick="btn_Submit_Click" />
        </div>
    </form>
</body>
</html>

```


## 個人認為完成作業須具備觀念

需要有一些基本的概念。


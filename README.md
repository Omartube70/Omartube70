تمام، فهمت قصدك. مشكلة إن المحتوى "بيطلع بره الصفحة" دي بتحصل غالبًا لما يكون في عناصر عرضها ثابت (زي الصور والإحصائيات) والصفحة بتتعرض على شاشة أصغر (زي الموبايل أو نافذة متصفح صغيرة).

الحل هو إني أعدل الكود عشان يكون متجاوب (Responsive) ويتكيف مع أي حجم شاشة. التعديلات اللي عملتها هي:

1.  **قسم "عني":** غيرت طريقة عرض الصورة المتحركة والكود اللي جنبها. بدل ما كانوا جنب بعض بشكل ممكن يسبب المشكلة، حطيتهم في جدول HTML غير مرئي. ده بيضمن إن كل حا-جة تفضل في مكانها الصحيح مهما كان حجم الشاشة.
2.  **الإحصائيات والصور المتحركة:** خليت أقصى عرض ليهم هو 100% من المساحة المتاحة، فبكده هيصغروا تلقائيًا مع الشاشة ومش هيخرجوا براها.

اتفضل الكود الجديد والمعدّل، جربه دلوقتي والمفروض المشكلة تكون اتحلت تمامًا.

-----

### الكود الجديد (بعد التعديل ليناسب كل الشاشات)

```markdown
<div align="center">

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Waving%20Hand.png" alt="Waving Hand" width="35" />
<h1>مرحباً، أنا Omar Mohamed</h1>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=5B2A91&center=true&vCenter=true&width=450&lines=%F0%9F%92%BB+.NET+Back-End+Developer;%E2%9A%99%EF%B8%8F+Building+RESTful+APIs;%F0%9F%97%83%EF%B8%8F+SQL+Server+Expert;%F0%9F%9A%80+Clean+Architecture+Advocate" alt="Typing SVG" style="max-width: 90%;"/>

<a href="https://github.com/Omartube70" target="_blank">
  <img src="https://komarev.com/ghpvc/?username=Omartube70&style=flat-square&color=5B2A91" alt="Profile views" />
</a>

</div>

---

## 🧑‍💻 **عني**

<table>
  <tr>
    <td valign="top">
<pre>
<code>
class OmarDeveloper
{
    public string Name { get; set; } = "Omar Mohamed";
    public string Role { get; set; } = ".NET Back-End Developer";
    public string[] Languages { get; set; } = { "C#", "C++" };
    public string[] Technologies { get; set; } = 
    {
        "💻 .NET",
        "🔗 RESTful APIs",
        "🗃️ Entity Framework & ADO.NET",
        "🏛️ Clean Architecture",
        "💾 SQL Server"
    };

    public void SayHi()
    {
        Console.WriteLine("مرحباً! أقوم ببناء خدمات خلفية قوية ومتطورة باستخدام .NET 🚀");
    }
}
</code>
</pre>
    </td>
    <td valign="top" width="400">
      <img alt="Coding" src="https://raw.githubusercontent.com/devSouvik/devSouvik/master/gif3.gif" style="max-width: 100%;"/>
    </td>
  </tr>
</table>

---

## 🛠️ **التقنيات والأدوات**

<div align="center">

### **Languages & Frameworks**
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-512BD4?style=for-the-badge&logo=.net&logoColor=white)

### **Database**
![Microsoft SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

### **Tools & Platforms**
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![SSMS](https://img.shields.io/badge/SSMS-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)


</div>

---

## 📊 **إحصائيات GitHub**

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Omartube70&show_icons=true&theme=react&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=5B2A91&icon_color=61DAFB&text_color=C9D1D9" alt="Omar's GitHub Stats" style="max-width:100%;"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Omartube70&layout=compact&theme=react&hide_border=true&bg_color=0D1117&title_color=5B2A91&text_color=C9D1D9&langs_count=8" alt="Omar's Top Languages" style="max-width:100%;"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Omartube70&theme=react&hide_border=true&background=0D1117&stroke=5B2A91&ring=5B2A91&fire=FF6B35&currStreakLabel=5B2A91" alt="GitHub Streak" style="max-width:100%;"/>

</div>

---

## 🌐 **تواصل معي**

<div align="center">

<a href="https://www.facebook.com/omar.mohamed.862034" target="_blank">
  <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"/>
</a>
<a href="mailto:omartubefaheen@gmail.com" target="_blank">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
</a>
<a href="https://github.com/Omartube70" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

</div>

---

## ⚡ **حقائق سريعة**

- 🔭 أعمل حالياً على: **مشاريع تدريبية لتطوير تطبيقات .NET**
- 🌱 أتعلم: **Docker وتطبيقات الـ Microservices**
- 💬 اسألني عن أي شيء يخص: **C#, .NET, SQL, and Clean Architecture**
- 🏢 أنا عضو في فريق: **[The CodeFather](https://thecodefather.netlify.app/)**

---

<div align="center">

## 💙 **شكراً لزيارتك!**

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Folded%20Hands.png" alt="Thank You" width="50" />

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,5,15&height=150&section=footer&reversal=false&textBg=false"/>
```

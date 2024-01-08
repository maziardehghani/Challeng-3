# Challeng-3
solve crime mystery that happend in mellat park yesterday
<html>

  <head>
    <title>مسابقه شماره ۱ | جنایت</title>
    <meta content="text/html" charset="UTF-8">
    <meta name="fontiran.com:license" content="56AXFY">
    <link rel="shortcut icon" type="image/png" href="/static/images/logo/favicon/favicon-16x16.2-4bcbe4f363d7.png" />
    <meta name="theme-color" content="#09c">
    


  <script>
    /* beautify ignore:start */
    (function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src='https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);})(window,document,'script','dataLayer','GTM-TDRQP6V');
    /* beautify ignore:end */
  </script>
  
    <script>
  const pendoApiKey = "3be06675-582d-4b57-7ae9-20805968b474" || null;
  const pendoVisitorID = "MTU3OTc0MTU3OTc0MTU3OfVJ1rIdtvbvvEgbB490xbE=" || null;
  // console.log("***", {pendoApiKey, pendoVisitorID});
  if (pendoApiKey && pendoVisitorID) {
    (function(apiKey) {
      (function(p, e, n, d, o) {
        var v, w, x, y, z;
        o = p[d] = p[d] || {};
        o._q = o._q || [];
        v = ['initialize', 'identify', 'updateOptions', 'pageLoad', 'track'];
        for (w = 0, x = v.length; w < x; ++w)(function(m) {
          o[m] = o[m] || function() {
            o._q[m === v[0] ? 'unshift' : 'push']([m].concat([].slice.call(arguments, 0)));
          };
        })(v[w]);
        y = e.createElement(n);
        y.async = !0;
        y.src = 'https://cdn.pendo.io/agent/static/' + apiKey + '/pendo.js';
        z = e.getElementsByTagName(n)[0];
        z.parentNode.insertBefore(y, z);
      })(window, document, 'script', 'pendo');

      // Call this whenever information about your visitors becomes available
      // Please use Strings, Numbers, or Bools for value types.
      pendo.initialize({
        visitor: {
          id: pendoVisitorID // Required if user is logged in
          // email:        // Recommended if using Pendo Feedback, or NPS Email
          // full_name:    // Recommended if using Pendo Feedback
          // role:         // Optional

          // You can add any additional visitor level key-values here,
          // as long as it's not one of the above reserved names.
        },

        account: {
          id: pendoVisitorID // Highly recommended
          // name:         // Optional
          // is_paying:    // Recommended if using Pendo Feedback
          // monthly_value:// Recommended if using Pendo Feedback
          // planLevel:    // Optional
          // planPrice:    // Optional
          // creationDate: // Optional

          // You can add any additional account level key-values here,
          // as long as it's not one of the above reserved names.
        }
      });
    })(pendoApiKey); // '20d7851e-9124-4b79-6701-5b9f82641576'
  }
</script>

  
  
  
    <script>
  const clarityRegister = function(c, l, a, r, i, t, y) {
    c[a] = c[a] || function() {
      (c[a].q = c[a].q || []).push(arguments)
    };
    t = l.createElement(r);
    t.async = 1;
    t.src = "https://www.clarity.ms/tag/" + i;
    y = l.getElementsByTagName(r)[0];
    y.parentNode.insertBefore(t, y);
  };

  const clarityID = "egsk7hcbu0";
  // console.log("clarityID:", clarityID)
  if (clarityID) {
    clarityRegister(window, document, "clarity", "script", clarityID);
  }
</script>

  


    <script type="text/javascript" src="/static/vendor_common/common.min.2-18fa0a8721ee.js"></script>
    <link rel="stylesheet" type="text/css" href="/static/vendor/semantic/semantic.rtl.min.2-87f68286e0ba.css" />
    <link rel="stylesheet" type="text/css" href="/static/css/style.2-46491d0a7db9.css" />
    <link rel="stylesheet" type="text/css" href="/static/semanticui/style.2-b3ef4156e542.css" />
    <script type="text/javascript" src="/static/js/main.2-d263ad2294d7.js"></script>
    <script src="/static/vendor/prism/prism.min.2-5da0e75af4f0.js" data-manual></script>
    <script type="text/javascript" src="/static/js/notebook.2-0c223d43deb5.js"></script>
    <script type="text/javascript" src="/static/js/markdown-moratab.2-f616a1acd17e.js"></script>
    <link rel="stylesheet" type="text/css" href="/static/vendor/prism/prism.2-4d56c799bef3.css">
    <link rel="stylesheet" href="/static/vendor/katex/katex.min.2-852d91d247c4.css" />
    <style>
      @page {
        margin: 25mm 20mm;
      }

      @media print {

        pre,
        code {
          white-space: pre-wrap;
          /* Since CSS 2.1 */
          white-space: -moz-pre-wrap;
          /* Mozilla, since 1999 */
          white-space: -o-pre-wrap;
          /* Opera 7 */
          word-wrap: break-word;
          /* Internet Explorer 5.5+ */
        }
      }

      pre {
        background-color: #dce8ec !important
      }
    </style>
    
      <link rel="canonical" href="https://quera.org/contest/assignments/821/problems/2491" />
    
  </head>

  <body dir="rtl">
    
  <noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-TDRQP6V" height="0" width="0"
    style="display:none;visibility:hidden"></iframe></noscript>


    <div class="qu-problem-segment">
      

<div style="display: none;" id="description_md-2491">+ محدودیت زمان: ۱ ثانیه
+ محدودیت حافظه: ۲۵۶ مگابایت

----------
یک جنازه‌ در پارک ملت پیدا شده است. طبق گفته‌های پزشک قانونی، مقتول به وسیله‌ی شات-گان کشته شده و شلیک گلوله‌ی شات-گان در یک لحظه بین لحظه‌ی $L$ و لحظه‌ی $R$ (شامل این دو لحظه) اتفاق افتاده است. کاراگاه شمس می‌خواهد حداقل و حداکثر تعداد ممکن برای افراد حاضر در پارک هنگام شلیک گلوله را بداند. همکار کارآگاه شمس، مادام، لیستی از مظنونین تهیه کرده و طی بازپرسی متوجه شده که مظنون $i$ام از لحظه‌ی $l_i$ تا لحظه‌ی $r_i$(شامل این دو لحظه)، در پارک حضور داشته است. مادام می‌خواهد با استفاده از این اطلاعات اعداد مدنظر کاراگاه شمس را به او بگوید. البته این کار ساده‌ای نیست، پس به او کمک کنید!

**شلیک میتواند در لحظه‌ای اعشاری اتفاق بیفتد.**

# ورودی
خط اول ورودی شامل دو عدد $L$ و $R$ است.

خط دوم شامل عدد $n$ است که بیانگر تعداد مظنونین واقعه می‌باشد. سپس در $n$ خط بعد هریک شامل دو عدد $l_i$ و $r_i$ است.

$$0 \le L \le R \le 10^9$$

$$0 \le l_i \le r_i \le 10^9$$

$$1 \le n \le 5000$$

# خروجی
تنها خط خروجی باید شامل دو عدد باشد که برابر با کمترین و بیشترین تعداد ممکن برای افراد حاضر در لحظه‌ی شلیک شات-گان هستند.

# ورودی نمونه

```
6 10
4
1 8
6 8
7 10
8 9
```
# خروجی نمونه

```
1 4
```</div>
<div>
    <div class="ui center aligned fluid container">
        <h1>جنایت</h1>
    </div>
    <br/>
    <div class="description-html" id="description_html-2491"></div>
</div>

<script type="text/javascript">
    document.addEventListener('DOMContentLoaded', function() {
        render_problem_text('description_md-2491', 'description_html-2491');
    });
</script>
    </div>
    <script>
      document.addEventListener('DOMContentLoaded', function() {
        // open all <details> tags
        $('details').attr('open', '');
        // print!
        window.print();
      });
    </script>
  </body>

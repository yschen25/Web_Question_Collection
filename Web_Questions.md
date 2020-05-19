## Web Questions
<br/>

1. What Is The Difference Between Session, Cookie, Sessionstorage and Localstorage?

<table>
    <tr>
        <th>Type</th>
        <th>session</th>
        <th>cookie</th>
        <th>sessionStorage</th>
        <th>localStorage</th>
    </tr>
    <tr>
        <td>Storage location</td>
        <td>Server-side</td>
        <td>Client-side</td>
        <td>Client-side</td>
        <td>Client-side</td>
    </tr>
    <tr>
        <td>Maximum data size</td>
        <td>1024KB</td>
        <td>4K for one cookie, max 20 cookies for a website</td>
        <td>5M</td>
        <td>5M</td>
    </tr>
    <tr>
        <td>Expired Time</td>
        <td>If user doesn’t active for a long time which over expire time, the server-side will delete the session to
            save the space
        </td>
        <td><li>user can set expiration time for each cookies.</li> <li>It will expire after closing browser if it set on client-side
        </li></td>
        <td>The data clear automatically when the browser is closed</td>
        <td>The data <b>WILL NOT</b> be deleted when the browser is closed until user clear through JavaScript, browser cache /
            locally stored data
        </td>
    </tr>
    <tr>
        <td>Scope</td>
        <td>No</td>
        <td>Changes made are saved and available for all same-origin page</td>
        <td>Changes made are saved and available for the current page</td>
        <td>Changes made are saved and available for all same-origin page</td>
    </tr>
    <tr>
        <td>Security</td>
        <td>High</td>
        <td>Low</td>
        <td>Low</td>
        <td>Low</td>
    </tr>
    <tr>
        <td>Usability</td>
        <td>Easily to use</td>
        <td>The api is difficult to use</td>
        <td colspan="2">Has method setItem, getItem, removeItem, clear that easily to use</td>
    </tr>
    <tr>
        <td>HTTP Request</td>
        <td></td>
        <td>The data is sent back to the server for every HTTP request which cause performance problems</td>
        <td colspan="2">The data is <b>NOT</b> sent back to the server for every HTTP request</td>
    </tr>
    <tr>
        <td>Application</td>
        <td>Login</td>
        <td>Login, shopping cart, game scores</td>
        <td>Form</td>
        <td>Shopping cart</td>
    </tr>
</table>
<br/>

:white_check_mark: 2. How To Speed Up The Website?

> - Reduce the HTTP request : use sprite images, combine files...etc. <br/>
> - Use CDN. <br/>
> - Reduce redirects. <br/>
> - Delete unused code : remove spaces, commas, and other unnecessary characters. <br/>
> - Minify files : use gzip for file compression, to reduce the size of your CSS, HTML, and JavaScript files.
> - Defer lag file loading : ensure that the rest of your content can load without a delay. <br/>
> - Use asynchronous loading : the browser could continue loading other elements on the page at the same time. <br/>

> - Related Reference : [20 Ways to Speed Up Your Website](https://www.crazyegg.com/blog/speed-up-your-website/)
<br/>

:white_check_mark: 3. Explain The Meaning Of HTTP Status Code 200, 400, 403, 404, 500, 502. 

> ① 200 : Request success. <br/>
> ② 400 : Syntax error -> The reason usually is programming error. <br/>
> ③ 403 : Not allow to visit. <br/>
> ④ 404 : Page not found. <br/>
> ⑤ 500 : Server error -> There are lots of possibilities : .htaccess document setting error, database setting error...etc <br/>
> ⑥ 502 : Bad gateway -> Wait and reload or find mis.
<br/>

:white_check_mark: 4. What Is NPM?

> - NPM is short for Node Package Manager, it is an online library for download open-source javaScript projects,
we can manage packages via NPM.
<br/>

:white_check_mark: 4.1 Why Use NPM?
> - For example if we want to use jQuery, we used to download jQuery or include jQuery CDN url, but how about we need to use a lots of packages? NPM is a tool to solve this time-consuming things.

> - Related Reference : [從零開始: 使用NPM套件](https://medium.com/html-test/從零開始-使用npm套件-317beefdf182)
<br/><br/>

:white_check_mark: 5. What Is Webpack?

> - There are lots of prepressors and frameworks, We may need to compile ES6, SCSS, webpack can help us compile preprocessors to the code which browser can understand then bundle it, we can also use webpack to minify or optimize code...etc., which makes work efficiently.

> - Related Reference : [什麼是Webpack?](https://medium.com/i-am-mike/什麼是webpack-你需要webpack嗎-2d8f9658241d), [關於 Webpack](https://neighborhood999.github.io/webpack-tutorial-gitbook/Part1/), [Webpack 初學者教學課程](https://neighborhood999.github.io/webpack-tutorial-gitbook/Part1/)
<br/><br/>

:white_check_mark: 6. What Is Graceful Degradation And Progressive Enhancement?

> - **Graceful Degradation** : Building the website so it provides a good level of user experience in **modern browsers first**, then fix the problem for other browsers 

> - **Progressive Enhancement** : Building the website to keep all functions work properly for **all the browsers**, then optimize the website to support the newer browser, let the basic functionality will work on older systems.

> - Use progressive enhancement will cost more time and manpower in the begging, but easily to maintain. Use graceful degradation can make website online quickly. Choose which to use it depends on the requirements.

> - Related Reference : [認識優雅降級與漸進增強](http://augus-blog.logdown.com/posts/143403-graceful-degradation-and-progressive-enhancement)
<br/><br/>

7. How The Browser Renders A Web Page? 

<br/>

8. What Is SPA? Strength And Weakness?

> - SPA is short for single page application. 
One SPA is one web application, what it needs will loaded (HTML, CSS, JS) in one time request, to manipulate DOM don't need to refresh browser just JavaScript.
<br/>

> - Related Reference : [跟著小明一起搞懂技術名詞：MVC、SPA 與 SSR](https://medium.com/@hulitw/introduction-mvc-spa-and-ssr-545c941669e9)
<br/><br/>

8.1 How To Solve The SEO problem For SPA?

<br/>

8.2. What Is Defferience Between SPA And SSR?

> - Related Reference : [淺談SPA、SEO與SSR](https://juejin.im/entry/5bbbf852f265da0aea699497)
<br/>

9. What Is Gateway, API Gateway and API?

> - Related Reference : [Amazon API Gateway](https://aws.amazon.com/tw/api-gateway/features/), [什麼是 Amazon API Gateway？](https://docs.aws.amazon.com/zh_tw/apigateway/latest/developerguide/welcome.html)
<br/>

10. What Is REST API? Strength And Weakness?

<br/>

10.1 How To Solve The problem 11?

<br/>

10.2 What Is Dfferience Between REST API And HTTP API?

<br/>

11. What Is Token?

<br/>

12. What Is Web Accessibility?

> - Related Reference : [我們都應該了解的 無障礙網頁 概念](https://designtongue.me/website-accessibility/)
<br/>

12.1 How To Make It?

<br/>
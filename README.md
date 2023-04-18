
<!--
### Hi there 👋

**AbhijitSarode/AbhijitSarode** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


<h1 align="center">Hi there 👋   My name is Abhijit</h1>
<!-- <h3 align="center">Building tech, having fun!</h3> -->

I'm a software developer with a passion for constantly building awesome projects. I'm proficient in the MERN stack, which includes MongoDB, Express.js, React, and Node.js. I also enjoy competitive programming and have participated in various coding competitions and Hackathons.

My GitHub profile showcases my love for making both technically challenging and goofy projects. Whether it's building a custom API for a digital product or a silly fart machine to prank my friends🤭

I'm always looking for ways to improve my skills and challenge myself. I'm open to collaborating on projects with other developers, and I'm also happy to help others with any questions they may have about programming or development in genera

Feel free to browse through my GitHub repositories and reach out to me if you have any questions or just want to say hi!


<p align="left"> <img src="https://komarev.com/ghpvc/?username=abhijitsarode&label=Profile%20views&color=0e75b6&style=flat" alt="abhijitsarode" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=abhijitsarode" alt="abhijitsarode" /></a> </p>

<!-- - 🔭 I’m currently working on [building my own site](https://www.abhijitsarode.in) -->

### Blogs posts
<!-- BLOG-POST-LIST:START -->
 - 1 &lt;p&gt;If you&#39;ve ever worked on a web development project, you know how challenging it can be to manage CSS. As the complexity of a project increases, so does the need for organization and consistency in the code. That&#39;s where CSS methodologies come in. By providing a set of guidelines and best practices, CSS methodologies help developers create maintainable and scalable CSS code.&lt;/p&gt;
&lt;p&gt;In this blog post, we&#39;ll explore four popular CSS methodologies - OOCSS, ACSS, BEM, and SMACSS. We&#39;ll cover what each methodology is, how it works, and what benefits it offers. By the end of this post, you&#39;ll have a better understanding of how CSS methodologies can help you make informed choices for your web development projects.&lt;/p&gt;
&lt;p&gt;Before we dive into that, let&#39;s talk about what we&#39;ll be building and how we&#39;ll be using the same example to demonstrate all of these methodologies. We&#39;ll be building a simple card component that you might use on a website to display information about a product, service, or feature. This component will have a header, body, and footer section, along with a button to take the user to another page. We&#39;ll use this same example for each of the CSS methodologies that we&#39;ll discuss, so you can see how each approach differs in terms of syntax, organization, and philosophy.&lt;/p&gt;
&lt;p&gt;&lt;img src=&quot;https://cdn.hashnode.com/res/hashnode/image/upload/v1681790352294/e2cf8a2e-2eec-4153-8400-d93b8d434a0f.png&quot; alt class=&quot;image--center mx-auto&quot; /&gt;&lt;/p&gt;
&lt;h2 id=&quot;heading-oocss-object-oriented-css&quot;&gt;OOCSS &lpar;Object-Oriented CSS&rpar;&lt;/h2&gt;
&lt;p&gt;Object-Oriented CSS is a methodology that focuses on creating reusable and modular CSS code. The basic idea behind OOCSS is to separate the visual style of a website from its structural layout. This separation allows developers to create classes that can be reused across multiple elements on a website.&lt;/p&gt;
&lt;p&gt;The core principle of OOCSS is the separation of structure and skin. In OOCSS, structure refers to the layout and positioning of elements on a website, while skin refers to the visual style and appearance of those elements. By separating these two aspects, OOCSS allows developers to create classes that define structure and skin independently. This approach makes it easier to maintain and update a website&#39;s visual style without affecting its layout.&lt;/p&gt;
&lt;p&gt;OOCSS also promotes the use of classes instead of IDs for styling elements. This approach makes it easier to create reusable styles and ensures that styles can be applied to multiple elements on a website. By avoiding the use of IDs, OOCSS helps developers avoid specificity issues that can arise when working with CSS.&lt;/p&gt;
&lt;p&gt;&lt;strong&gt;HTML&lt;/strong&gt;&lt;/p&gt;
&lt;pre&gt;&lt;code class=&quot;lang-xml&quot;&gt;&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card-header&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;Card title&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card-body&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;
    &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;p&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card-text&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;This is some card text.&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;p&lt;/span&gt;&amp;gt;&lt;/span&gt;
    &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;button&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;btn btn-primary&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;Go somewhere&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;button&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
&lt;/code&gt;&lt;/pre&gt;
&lt;p&gt;&lt;strong&gt;CSS&lt;/strong&gt;&lt;/p&gt;
&lt;pre&gt;&lt;code class=&quot;lang-css&quot;&gt;&lt;span class=&quot;hljs-comment&quot;&gt;/***** Structure *****/&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.card&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;display&lt;/span&gt;: flex;
  &lt;span class=&quot;hljs-attribute&quot;&gt;flex-direction&lt;/span&gt;: column;
  &lt;span class=&quot;hljs-attribute&quot;&gt;width&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;400px&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin-bottom&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;20px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card-header&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;padding&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;10px&lt;/span&gt; &lt;span class=&quot;hljs-number&quot;&gt;15px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card-body&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;flex&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;padding&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;15px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card-text&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin-bottom&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;15px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.btn&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;display&lt;/span&gt;: inline-block;
  &lt;span class=&quot;hljs-attribute&quot;&gt;padding&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;10px&lt;/span&gt; &lt;span class=&quot;hljs-number&quot;&gt;20px&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;cursor&lt;/span&gt;: pointer;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/***** Skin *****/&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.card&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#fff&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; solid &lt;span class=&quot;hljs-number&quot;&gt;#ddd&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border-radius&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;4px&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;box-shadow&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt; &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; &lt;span class=&quot;hljs-number&quot;&gt;3px&lt;/span&gt; &lt;span class=&quot;hljs-built_in&quot;&gt;rgba&lt;/span&gt;&lpar;&lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;,&lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;,&lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;,.&lt;span class=&quot;hljs-number&quot;&gt;125&lt;/span&gt;&rpar;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card-header&lt;/span&gt; { 
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;18px&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-weight&lt;/span&gt;: bold;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border-bottom&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; solid &lt;span class=&quot;hljs-number&quot;&gt;#ddd&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card-text&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;16px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.btn&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;14px&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-weight&lt;/span&gt;: bold;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border-radius&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;4px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.btn-primary&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#007bff&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#fff&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border&lt;/span&gt;: none;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/***** State *****/&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.btn&lt;/span&gt;&lt;span class=&quot;hljs-selector-pseudo&quot;&gt;:hover&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;opacity&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;0.8&lt;/span&gt;;
}
&lt;/code&gt;&lt;/pre&gt;
&lt;p&gt;In OOCSS it is important to have a clear separation between Structure &amp;amp; Skin so that it allows for easy changes to the visual appearance without affecting the structure, and facilitates the creation of new styles by combining existing classes.&lt;/p&gt;
&lt;h2 id=&quot;heading-acss-atomic-css&quot;&gt;ACSS &lpar;Atomic CSS&rpar;&lt;/h2&gt;
&lt;p&gt;Atomic CSS is a methodology that emphasizes the use of small, single-purpose classes. Each class in ACSS is designed to apply a specific style to a single element on a website. This approach makes it easier to create and manage styles, as each class serves a single purpose.&lt;/p&gt;
&lt;p&gt;The core principle of ACSS is the use of atomic classes. An atomic class is a single-purpose class that applies a specific style to an element. Atomic classes are typically named based on the style they apply, such as .font-size-small or .bg-color-blue. By using atomic classes, developers can easily create and manage styles without having to worry about the specificity of CSS.&lt;/p&gt;
&lt;p&gt;ACSS also promotes the use of utility classes. Utility classes are classes that apply a specific style to an element, such as .hide or .clearfix. Utility classes are designed to be used across a website and provide a consistent set of styles that can be applied to different elements.&lt;/p&gt;
&lt;p&gt;&lt;strong&gt;HTML&lt;/strong&gt;&lt;/p&gt;
&lt;pre&gt;&lt;code class=&quot;lang-xml&quot;&gt;&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;d-fx_flex fd-col w-400 bg-white bd-1 bdrs-4 box-s_0_1_3_ddd mb-20&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;p-10_15 fs-18 fw-bold bd-btm-1_ddd&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;Card title&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;flex-1 p-15&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;
    &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;p&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;fs-16 mb-15&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;This is some card text.&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;p&lt;/span&gt;&amp;gt;&lt;/span&gt;
    &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;button&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;btn bg-blue cl-white bd-none p-10_20 bdrs-4 cur-ptr&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;Go somewhere&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;button&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
&lt;/code&gt;&lt;/pre&gt;
&lt;p&gt;&lt;strong&gt;CSS&lt;/strong&gt;&lt;/p&gt;
&lt;pre&gt;&lt;code class=&quot;lang-css&quot;&gt;&lt;span class=&quot;hljs-comment&quot;&gt;/* Align container horizontally */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.d-fx_flex&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;display&lt;/span&gt;: flex;
  &lt;span class=&quot;hljs-attribute&quot;&gt;flex-direction&lt;/span&gt;: row;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Align container vertically */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.fd-col&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;flex-direction&lt;/span&gt;: column;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the width of an element to 400px */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.w-400&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;width&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;400px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the background color of an element to white */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.bg-white&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#fff&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the border of an element to 1px */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.bd-1&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;border&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; solid;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the border-radius of an element to 4px */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.bdrs-4&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;border-radius&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;4px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the box-shadow of an element */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.box-s_0_1_3_ddd&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;box-shadow&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt; &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; &lt;span class=&quot;hljs-number&quot;&gt;3px&lt;/span&gt; &lt;span class=&quot;hljs-built_in&quot;&gt;rgba&lt;/span&gt;&lpar;&lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;,&lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;,&lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;,.&lt;span class=&quot;hljs-number&quot;&gt;125&lt;/span&gt;&rpar;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the margin-bottom of an element to 20px */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.mb-20&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin-bottom&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;20px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the padding of an element */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.p-10_15&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;padding&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;10px&lt;/span&gt; &lt;span class=&quot;hljs-number&quot;&gt;15px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the font size of an element to 18px */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.fs-18&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;18px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the font weight of an element to bold */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.fw-bold&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-weight&lt;/span&gt;: bold;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the border-bottom of an element */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.bd-btm-1_ddd&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;border-bottom&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; solid &lt;span class=&quot;hljs-number&quot;&gt;#ddd&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Make an element fill the remaining space in a container */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.flex-1&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;flex&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the padding of an element to 15px */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.p-15&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;padding&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;15px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the font size of an element to 16px */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.fs-16&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;16px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the margin-bottom of an element to 15px */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.mb-15&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin-bottom&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;15px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Define a button style */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.btn&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;display&lt;/span&gt;: inline-block;
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-weight&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;400&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#212529&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;text-align&lt;/span&gt;: center;
  &lt;span class=&quot;hljs-attribute&quot;&gt;vertical-align&lt;/span&gt;: middle;
  &lt;span class=&quot;hljs-attribute&quot;&gt;-webkit-user-select&lt;/span&gt;: none;
  &lt;span class=&quot;hljs-attribute&quot;&gt;-moz-user-select&lt;/span&gt;: none;
  &lt;span class=&quot;hljs-attribute&quot;&gt;-ms-user-select&lt;/span&gt;: none;
  &lt;span class=&quot;hljs-attribute&quot;&gt;user-select&lt;/span&gt;: none;
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: transparent;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; solid transparent;
  &lt;span class=&quot;hljs-attribute&quot;&gt;padding&lt;/span&gt;: .&lt;span class=&quot;hljs-number&quot;&gt;375rem&lt;/span&gt; .&lt;span class=&quot;hljs-number&quot;&gt;75rem&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1rem&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;line-height&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1.5&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border-radius&lt;/span&gt;: .&lt;span class=&quot;hljs-number&quot;&gt;25rem&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;transition&lt;/span&gt;: color .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out,background-color .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out,border-color .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out,box-shadow .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the background color of a button */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.bg-blue&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#007bff&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the text color of a button to white*/&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.cl-white&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;color&lt;/span&gt;: white;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Remove the border of an element */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.bd-none&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;border&lt;/span&gt;: none;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the cursor style of an element to pointer */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.cur-ptr&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;cursor&lt;/span&gt;: pointer;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the padding of a button */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.p-10_20&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;padding&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;10px&lt;/span&gt; &lt;span class=&quot;hljs-number&quot;&gt;20px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/* Set the border-radius of an element to 4px */&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.bdrs-4&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;border-radius&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;4px&lt;/span&gt;;
}
&lt;/code&gt;&lt;/pre&gt;
&lt;p&gt;In ACSS, it&#39;s important to use clear and descriptive class names and to be consistent in how those class names are structured. The comments in this code sample help explain what each class does and how it fits into the ACSS methodology.&lt;/p&gt;
&lt;h2 id=&quot;heading-bem-block-element-modifier&quot;&gt;BEM &lpar;Block, Element, Modifier&rpar;&lt;/h2&gt;
&lt;p&gt;Block, Element, and Modifier is a methodology that focuses on creating modular and reusable CSS code. BEM is based on the concept of components, which are self-contained pieces of code that can be reused across a website.&lt;/p&gt;
&lt;p&gt;The core principle of BEM is the use of the block, element and modifier naming convention. A block is a standalone component on a website, such as a header or a footer. An element is a part of a block, such as a button or a link within a header. A modifier is a variation of a block or element, such as a disabled button or a highlighted link.&lt;/p&gt;
&lt;p&gt;By using the block, element, and modifier naming convention, BEM makes it easier to create reusable and modular CSS code. BEM also promotes the use of classes for styling elements and encourages developers to avoid using IDs.&lt;/p&gt;
&lt;p&gt;&lt;strong&gt;HTML&lt;/strong&gt;&lt;/p&gt;
&lt;pre&gt;&lt;code class=&quot;lang-xml&quot;&gt;&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card card--featured&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card__header&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;
    &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;h2&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card__title&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;Card Title&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;h2&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card__body&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;
    &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;p&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card__text&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;This is some card text.&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;p&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card__footer&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;
    &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;a&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;href&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;#&quot;&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;btn btn--primary card__button&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;Go somewhere&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;a&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
&lt;/code&gt;&lt;/pre&gt;
&lt;p&gt;&lt;strong&gt;CSS&lt;/strong&gt;&lt;/p&gt;
&lt;pre&gt;&lt;code class=&quot;lang-css&quot;&gt;&lt;span class=&quot;hljs-comment&quot;&gt;/***** Block *****/&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.card&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;display&lt;/span&gt;: flex;
  &lt;span class=&quot;hljs-attribute&quot;&gt;flex-direction&lt;/span&gt;: column;
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#fff&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; solid &lt;span class=&quot;hljs-number&quot;&gt;#ddd&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border-radius&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;4px&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;box-shadow&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt; &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; &lt;span class=&quot;hljs-number&quot;&gt;3px&lt;/span&gt; &lt;span class=&quot;hljs-built_in&quot;&gt;rgba&lt;/span&gt;&lpar;&lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;,&lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;,&lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;,.&lt;span class=&quot;hljs-number&quot;&gt;125&lt;/span&gt;&rpar;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin-bottom&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;20px&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;padding&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;15px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/***** Element *****/&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.card__header&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin-bottom&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;15px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card__title&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;18px&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-weight&lt;/span&gt;: bold;
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card__body&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin-bottom&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;15px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card__text&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;16px&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card__footer&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;display&lt;/span&gt;: flex;
  &lt;span class=&quot;hljs-attribute&quot;&gt;justify-content&lt;/span&gt;: flex-end;
  &lt;span class=&quot;hljs-attribute&quot;&gt;align-items&lt;/span&gt;: center;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card__button&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;display&lt;/span&gt;: inline-block;
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-weight&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;400&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#212529&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;text-align&lt;/span&gt;: center;
  &lt;span class=&quot;hljs-attribute&quot;&gt;vertical-align&lt;/span&gt;: middle;
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: transparent;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; solid transparent;
  &lt;span class=&quot;hljs-attribute&quot;&gt;padding&lt;/span&gt;: .&lt;span class=&quot;hljs-number&quot;&gt;375rem&lt;/span&gt; .&lt;span class=&quot;hljs-number&quot;&gt;75rem&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1rem&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;line-height&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1.5&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border-radius&lt;/span&gt;: .&lt;span class=&quot;hljs-number&quot;&gt;25rem&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;transition&lt;/span&gt;: color .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out,background-color .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out,border-color .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out,box-shadow .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/***** Modifier *****/&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.card--featured&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#f5f5f5&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.btn--primary&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#007bff&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#fff&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.btn--primary&lt;/span&gt;&lt;span class=&quot;hljs-selector-pseudo&quot;&gt;:hover&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#0069d9&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#fff&lt;/span&gt;;
}
&lt;/code&gt;&lt;/pre&gt;
&lt;p&gt;In BEM, we start with a block class that represents a higher-level component and then use element classes to represent nested components within that block. We can also use modifier classes to change the appearance or behavior of the block or its elements. The class names follow a strict naming convention, with double underscores &lpar;__&rpar; separating block and element names, and double hyphens &lpar;--&rpar; separating block or element names from modifier names. This helps to create a clear and consistent naming structure for our CSS classes.&lt;/p&gt;
&lt;h2 id=&quot;heading-smacss-scalable-and-modular-architecture-for-css&quot;&gt;SMACSS &lpar;Scalable and Modular Architecture for CSS &rpar;&lt;/h2&gt;
&lt;p&gt;Scalable &amp;amp; Modular Architecture is a methodology that focuses on creating flexible and maintainable CSS code. SMACSS is based on the idea that CSS should be structured in a way that reflects the architecture of a website.&lt;/p&gt;
&lt;p&gt;The core principle of SMACSS is the separation of concerns. In SMACSS, CSS is divided into five categories: Base, Layout, Module, State, and Theme. Each category represents a different aspect of a website&#39;s design, such as the basic styles &lpar;Base&rpar;, the overall layout &lpar;Layout&rpar;, and individual components &lpar;Module&rpar;.&lt;/p&gt;
&lt;p&gt;By dividing CSS into categories, SMACSS makes it easier to organize and maintain CSS code. SMACSS also promotes the use of classes for styling elements and encourages developers to avoid using IDs.&lt;/p&gt;
&lt;p&gt;&lt;strong&gt;HTML&lt;/strong&gt;&lt;/p&gt;
&lt;pre&gt;&lt;code class=&quot;lang-xml&quot;&gt;&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card-header&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;
    &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;h2&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card-title&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;Card Title&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;h2&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card-body&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;
    &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;p&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card-text&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;This is some card text&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;p&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;card-footer&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;
    &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;&lt;span class=&quot;hljs-name&quot;&gt;a&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;href&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;#&quot;&lt;/span&gt; &lt;span class=&quot;hljs-attr&quot;&gt;class&lt;/span&gt;=&lt;span class=&quot;hljs-string&quot;&gt;&quot;btn btn-primary card-button&quot;&lt;/span&gt;&amp;gt;&lt;/span&gt;Go somewhere&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;a&lt;/span&gt;&amp;gt;&lt;/span&gt;
  &lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
&lt;span class=&quot;hljs-tag&quot;&gt;&amp;lt;/&lt;span class=&quot;hljs-name&quot;&gt;div&lt;/span&gt;&amp;gt;&lt;/span&gt;
&lt;/code&gt;&lt;/pre&gt;
&lt;p&gt;&lt;strong&gt;CSS&lt;/strong&gt;&lt;/p&gt;
&lt;pre&gt;&lt;code class=&quot;lang-css&quot;&gt;&lt;span class=&quot;hljs-comment&quot;&gt;/***** Base styles *****/&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.card&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#fff&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; solid &lt;span class=&quot;hljs-number&quot;&gt;#ddd&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border-radius&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;4px&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;box-shadow&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt; &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; &lt;span class=&quot;hljs-number&quot;&gt;3px&lt;/span&gt; &lt;span class=&quot;hljs-built_in&quot;&gt;rgba&lt;/span&gt;&lpar;&lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;,&lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;,&lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;,.&lt;span class=&quot;hljs-number&quot;&gt;125&lt;/span&gt;&rpar;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;padding&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;15px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card-title&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;18px&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-weight&lt;/span&gt;: bold;
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card-text&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;16px&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;0&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card-button&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;display&lt;/span&gt;: inline-block;
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-weight&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;400&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#212529&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;text-align&lt;/span&gt;: center;
  &lt;span class=&quot;hljs-attribute&quot;&gt;vertical-align&lt;/span&gt;: middle;
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: transparent;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; solid transparent;
  &lt;span class=&quot;hljs-attribute&quot;&gt;padding&lt;/span&gt;: .&lt;span class=&quot;hljs-number&quot;&gt;375rem&lt;/span&gt; .&lt;span class=&quot;hljs-number&quot;&gt;75rem&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1rem&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;line-height&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1.5&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border-radius&lt;/span&gt;: .&lt;span class=&quot;hljs-number&quot;&gt;25rem&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;transition&lt;/span&gt;: color .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out,background-color .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out,border-color .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out,box-shadow .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.btn&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;display&lt;/span&gt;: inline-block;
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-weight&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;400&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#212529&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;text-align&lt;/span&gt;: center;
  &lt;span class=&quot;hljs-attribute&quot;&gt;vertical-align&lt;/span&gt;: middle;
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: transparent;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1px&lt;/span&gt; solid transparent;
  &lt;span class=&quot;hljs-attribute&quot;&gt;padding&lt;/span&gt;: .&lt;span class=&quot;hljs-number&quot;&gt;375rem&lt;/span&gt; .&lt;span class=&quot;hljs-number&quot;&gt;75rem&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;font-size&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1rem&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;line-height&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;1.5&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;border-radius&lt;/span&gt;: .&lt;span class=&quot;hljs-number&quot;&gt;25rem&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;transition&lt;/span&gt;: color .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out,background-color .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out,border-color .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out,box-shadow .&lt;span class=&quot;hljs-number&quot;&gt;15s&lt;/span&gt; ease-in-out;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.btn-primary&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#007bff&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#fff&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.btn-primary&lt;/span&gt;&lt;span class=&quot;hljs-selector-pseudo&quot;&gt;:hover&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;background-color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#0069d9&lt;/span&gt;;
  &lt;span class=&quot;hljs-attribute&quot;&gt;color&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;#fff&lt;/span&gt;;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/***** Layout *****/&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.card&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;display&lt;/span&gt;: flex;
  &lt;span class=&quot;hljs-attribute&quot;&gt;flex-direction&lt;/span&gt;: column;
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin-bottom&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;20px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card-header&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin-bottom&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;15px&lt;/span&gt;;
}

&lt;span class=&quot;hljs-selector-class&quot;&gt;.card-body&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin-bottom&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;15px&lt;/span&gt;;
}


&lt;span class=&quot;hljs-selector-class&quot;&gt;.card-footer&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;display&lt;/span&gt;: flex;
  &lt;span class=&quot;hljs-attribute&quot;&gt;justify-content&lt;/span&gt;: flex-end;
  &lt;span class=&quot;hljs-attribute&quot;&gt;align-items&lt;/span&gt;: center;
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin-top&lt;/span&gt;: auto;
}

&lt;span class=&quot;hljs-comment&quot;&gt;/***** Module *****/&lt;/span&gt;
&lt;span class=&quot;hljs-selector-class&quot;&gt;.card-button&lt;/span&gt; {
  &lt;span class=&quot;hljs-attribute&quot;&gt;margin-left&lt;/span&gt;: &lt;span class=&quot;hljs-number&quot;&gt;10px&lt;/span&gt;;
}
&lt;/code&gt;&lt;/pre&gt;
&lt;p&gt;State styles &amp;amp; Theme styles are not used in this particular example, but State styles would be &lt;code&gt;:hover&lt;/code&gt; or &lt;code&gt;:active&lt;/code&gt; and Theme styles would be the overall look and feel of the site, such as colors and typography&lt;/p&gt;
&lt;h2 id=&quot;heading-which-css-methodology-should-you-use&quot;&gt;Which CSS Methodology Should You Use?&lt;/h2&gt;
&lt;p&gt;Choosing a CSS methodology can be a difficult decision, as each methodology offers its own set of benefits and drawbacks. The best CSS methodology for your project will depend on a variety of factors, such as the size and complexity of the website, the number of developers working on the project, and your personal preferences and experience.&lt;/p&gt;
&lt;p&gt;Here are a few factors to consider when choosing a CSS methodology:&lt;/p&gt;
&lt;ul&gt;
&lt;li&gt;&lt;p&gt;&lt;strong&gt;Reusability&lt;/strong&gt;: If you&#39;re working on a website with many components that have similar styles, OOCSS or BEM may be a good choice, as they both emphasize the creation of reusable and modular CSS code.&lt;/p&gt;
&lt;/li&gt;
&lt;li&gt;&lt;p&gt;&lt;strong&gt;Scalability&lt;/strong&gt;: If you&#39;re working on a large website that requires a lot of styles, ACSS or SMACSS may be a good choice, as they both focus on creating flexible and maintainable CSS code.&lt;/p&gt;
&lt;/li&gt;
&lt;li&gt;&lt;p&gt;&lt;strong&gt;Team Size&lt;/strong&gt;: If you&#39;re working on a project with a large team of developers, a methodology like BEM or SMACSS may be a good choice, as they both offer clear guidelines and naming conventions that can help ensure consistency across the codebase.&lt;/p&gt;
&lt;/li&gt;
&lt;li&gt;&lt;p&gt;&lt;strong&gt;Personal preference&lt;/strong&gt;: Ultimately, the CSS methodology you choose will depend on your personal preferences and experience. Take some time to experiment with different methodologies and find the one that works best for you.&lt;/p&gt;
&lt;/li&gt;
&lt;/ul&gt;
&lt;h2 id=&quot;heading-conclusion&quot;&gt;Conclusion&lt;/h2&gt;
&lt;p&gt;In conclusion, CSS methodologies can be a valuable tool for web developers looking to create maintainable, scalable, and performant CSS code. Whether you choose OOCSS, ACSS, BEM, SMACSS, or another methodology entirely, the key is to find a system that works for you and your team. By investing in good CSS practices, you&#39;ll be well on your way to creating high-quality, maintainable websites that look great and perform well.&lt;/p&gt;
&lt;p&gt;Remember that CSS methodologies are just a starting point. They provide a set of guidelines and best practices that can help you to make informed choices for your web development projects. It&#39;s up to you to adapt and modify these methodologies to suit your specific needs and goals.&lt;/p&gt;
&lt;p&gt;So take some time to explore different CSS methodologies, experiment with different approaches, and find the one that works best for you. By doing so, you&#39;ll be well on your way to becoming a more effective and efficient web developer.&lt;/p&gt;
&lt;p&gt;&lt;strong&gt;Footnote&lt;/strong&gt;: I welcome any feedback, comments, or corrections on this article. If you notice any errors or have suggestions for improvement, please feel free to reach out to me. Your insights are valuable and will help me to grow as a writer. Thank you!&lt;/p&gt;
 [CSS Methodologies Demystified: An Introduction to OOCSS, ACSS, BEM, and SMACSS](https://abhijitsarode.hashnode.dev/css-methodologies-demystified-an-introduction-to-oocss-acss-bem-and-smacss) <!-- BLOG-POST-LIST:END -->

<h3 align="left">Connect with me:</h3>
<p align="left">
<!--twitter-->
<a href="https://twitter.com/abhijit_ras" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="abhijit_ras" height="30" width="40" /></a>
<!-- hashnode -->
<a href="https://hashnode.com/@abhijitsarode" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hashnode.svg" alt="@abhijitsarode" height="30" width="40" /></a>
<!-- leetcode   -->
<a href="https://www.leetcode.com/abhijitsarode" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="abhijitsarode" height="30" width="40" /></a>
<!-- codewars   -->
<!-- <a href="https://www.codewars.com/users/AbhijitSarode" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codeforces.svg" alt="https://www.codewars.com/users/abhijitsarode" height="30" width="40" /></a>
</p> -->
<!-- email -->

Alternatively you can [click here](mailto:sarode.abhijit14@gmail.com?subject=Hello%20from%20GitHub&body=Hi%20there%2C%0D%0A%0D%0AI%20came%20across%20your%20GitHub%20profile%20and%20would%20love%20to%20connect%20with%20you%20about%20potential%20collaborations.%20Let%20me%20know%20if%20you%27re%20interested.%0D%0A%0D%0ABest%20Regards%2C%0D%0A%0D%0A[Your%20Name]) to open a pre-filled email in your default email client.





<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.blender.org/" target="_blank" rel="noreferrer"> <img src="https://download.blender.org/branding/community/blender_community_badge_white.svg" alt="blender" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://heroku.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="40" height="40"/> </a> <a href="https://threejs.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Three.js_Icon.svg" alt="threejs" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://nextjs.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://www.sketch.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sketchapp/sketchapp-icon.svg" alt="sketch" width="40" height="40"/>
</a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=abhijitsarode&show_icons=true&locale=en&layout=compact" alt="abhijitsarode" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=abhijitsarode&show_icons=true&locale=en" alt="abhijitsarode" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=abhijitsarode&" alt="abhijitsarode" /></p>

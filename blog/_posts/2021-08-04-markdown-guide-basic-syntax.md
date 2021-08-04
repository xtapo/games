---
layout: post
title:  Basic Syntax | Markdown Guide
image:  
  path: /assets/img/blog/1200px-Markdown-mark.svg.png
canonical_url: https://photos.xtapo.com
hide_image: false
accent_color: '#4fb1ba'
accent_image:
  background: 'linear-gradient(to bottom,#193747 0%,#233e4c 30%,#3c929e 50%,#d5d5d4 70%,#cdccc8 100%)'
  overlay:    true
categories: [blog]
description: >
  Đăng ký Office 365 miễn phí là phần mềm hữu hiệu để cung cấp cho bạn quyền truy cập vào các công cụ Microsoft Office đã biết ở bất cứ nơi đâu...

tag: Markdown, Guide
---


<!DOCTYPE html>
<html lang="en">
  <head>



  <meta charset="utf-8">


  <title>Basic Syntax | Markdown Guide</title>

  <meta name="description" content="The Markdown elements outlined in John Gruber's design document.">
  <meta name="twitter:card" content="summary" />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://www.markdownguide.org/basic-syntax/" />
  <meta property="og:title" content="Basic Syntax | Markdown Guide" />
  <meta property="og:description" content="The Markdown elements outlined in John Gruber's design document." />
  <meta property="og:image" content="https://www.markdownguide.org/assets/images/markdown-guide-og.jpg" />

  <meta name="HandheldFriendly" content="True">
  <meta name="MobileOptimized" content="320">

  <link rel='stylesheet' href='https://d33wubrfki0l68.cloudfront.net/bundles/257fcefa15c80677a39e88c7592ab770b9744ccb.css'/>







  <link rel="canonical" href="https://www.markdownguide.org/basic-syntax/">

  <script async src='https://d33wubrfki0l68.cloudfront.net/js/b92d1d6792dcd0d18e09ab7ac797f58e0550bd7c/assets/javascript/jquery-3.5.1.slim.min.js'></script>
  <script async src='https://d33wubrfki0l68.cloudfront.net/bundles/b5975b78fdc2f6b186ff2607bcc7827fa767d566.js'></script>
  <script defer src='https://d33wubrfki0l68.cloudfront.net/bundles/1066bc339a3beded5f6c4279870b406c047460fe.js'></script>

</head>

  <body data-spy="scroll" data-target="#toc">


    <!-- Main jumbotron for a primary marketing message or call to action -->
    <div class="jumbotron">
      <div class="container">
        <h1 class="no-anchor" data-toc-skip>Basic Syntax</h1>
        <p>The Markdown elements outlined in John Gruber's design document.</p>
      </div>
    </div>
    <div class="container">
      <div class="row row-offcanvas row-offcanvas-right">
        <div class="col-xs-12 col-sm-12 col-md-9">

<h2>Overview</h2>

<p>Nearly all Markdown applications support the basic syntax outlined in John Gruber’s original design document. There are minor variations and discrepancies between Markdown processors — those are noted inline wherever possible.</p>

<h2>Headings</h2>

<p>To create a heading, add number signs (<code class="language-plaintext highlighter-rouge">#</code>) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three (<code class="language-plaintext highlighter-rouge">&lt;h3&gt;</code>), use three number signs (e.g., <code class="language-plaintext highlighter-rouge">### My Header</code>).</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge"># Heading level 1</code></td>
      <td><code class="highlighter-rouge">&lt;h1&gt;Heading level 1&lt;/h1&gt;</code></td>
      <td><h1 class="no-anchor" data-toc-skip="">Heading level 1</h1></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">## Heading level 2</code></td>
      <td><code class="highlighter-rouge">&lt;h2&gt;Heading level 2&lt;/h2&gt;</code></td>
      <td><h2 class="no-anchor" data-toc-skip="">Heading level 2</h2></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">### Heading level 3</code></td>
      <td><code class="highlighter-rouge">&lt;h3&gt;Heading level 3&lt;/h3&gt;</code></td>
      <td><h3 class="no-anchor" data-toc-skip="">Heading level 3</h3></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">#### Heading level 4</code></td>
      <td><code class="highlighter-rouge">&lt;h4&gt;Heading level  4&lt;/h4&gt;</code></td>
      <td><h4 class="no-anchor">Heading level 4</h4></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">##### Heading level 5</code></td>
      <td><code class="highlighter-rouge">&lt;h5&gt;Heading level 5&lt;/h5&gt;</code></td>
      <td><h5 class="no-anchor">Heading level 5</h5></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">###### Heading level 6</code></td>
      <td><code class="highlighter-rouge">&lt;h6&gt;Heading level 6&lt;/h6&gt;</code></td>
      <td><h6 class="no-anchor">Heading level 6</h6></td>
    </tr>
  </tbody>
</table>

<h3 id="alternate-syntax">Alternate Syntax</h3>

<p>Alternatively, on the line below the text, add any number of <code class="language-plaintext highlighter-rouge">==</code> characters for heading level 1 or <code class="language-plaintext highlighter-rouge">--</code> characters for heading level 2.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">Heading level 1<br />===============</code></td>
      <td><code class="highlighter-rouge">&lt;h1&gt;Heading level 1&lt;/h1&gt;</code></td>
      <td><h1 class="no-anchor" data-toc-skip="">Heading level 1</h1></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Heading level 2<br />---------------</code></td>
      <td><code class="highlighter-rouge">&lt;h2&gt;Heading level 2&lt;/h2&gt;</code></td>
      <td><h2 class="no-anchor" data-toc-skip="">Heading level 2</h2></td>
    </tr>
  </tbody>
</table>

<h3 id="heading-best-practices">Heading Best Practices</h3>

<p>Markdown applications don’t agree on how to handle a missing space between the number signs (<code class="language-plaintext highlighter-rouge">#</code>) and the heading name. For compatibility, always put a space between the number signs and the heading name.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          # Here's a Heading<br /><br />
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          #Here's a Heading
        </code>
      </td>
    </tr>
  </tbody>
</table>

<p>You should also put blank lines before and after a heading for compatibility.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
        Try to put a blank line before...<br /><br />

        # Heading<br /><br />

        ...and after a heading.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        Without blank lines, this might not look right.<br />
        # Heading<br />
        Don't do this!
        </code>
      </td>
    </tr>
  </tbody>
</table>

<h2>Paragraphs</h2>

<p>To create paragraphs, use a blank line to separate one or more lines of text.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          I really like using Markdown.<br /><br />

          I think I'll use it to format all of my documents from now on.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">&lt;p&gt;I really like using Markdown.&lt;/p&gt;<br /><br />

        &lt;p&gt;I think I'll use it to format all of my documents from now on.&lt;/p&gt;</code>
      </td>
      <td>
        <p>I really like using Markdown.</p>

        <p>I think I'll use it to format all of my documents from now on.</p>
      </td>
    </tr>
  </tbody>
</table>

<h3 id="paragraph-best-practices">Paragraph Best Practices</h3>

<p>Unless the <a href="/basic-syntax/#paragraphs">paragraph is in a list</a>, don’t indent paragraphs with spaces or tabs.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          Don't put tabs or spaces in front of your paragraphs.<br /><br />

          Keep lines left-aligned like this.<br /><br />
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        &nbsp;&nbsp;&nbsp;&nbsp;This can result in unexpected
        formatting problems.<br /><br />

        &nbsp;&nbsp;Don't add tabs or spaces in front of paragraphs.
        </code>
      </td>
    </tr>
  </tbody>
</table>

<h2>Line Breaks</h2>

<p>To create a line break (<code class="language-plaintext highlighter-rouge">&lt;br&gt;</code>), end a line with two or more spaces, and then type return.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          This is the first line. &nbsp;<br />
          And this is the second line.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">&lt;p&gt;This is the first line.&lt;br&gt;<br />

        And this is the second line.&lt;/p&gt;</code>
      </td>
      <td>
        <p>This is the first line.<br />   
        And this is the second line.</p>
      </td>
    </tr>
  </tbody>
</table>

<h3 id="line-break-best-practices">Line Break Best Practices</h3>

<p>You can use two or more spaces (commonly referred to as “trailing whitespace”) for line breaks in nearly every Markdown application, but it’s controversial. It’s hard to see trailing whitespace in an editor, and many people accidentally or intentionally put two spaces after every sentence. For this reason, you may want to use something other than trailing whitespace for line breaks. If your Markdown application <a href="/basic-syntax/#html">supports HTML</a>, you can use the <code class="language-plaintext highlighter-rouge">&lt;br&gt;</code> HTML tag.</p>

<p>For compatibility, use trailing white space or the <code class="language-plaintext highlighter-rouge">&lt;br&gt;</code> HTML tag at the end of the line.</p>

<p>There are two other options I don’t recommend using. CommonMark and a few other lightweight markup languages let you type a backslash (<code class="language-plaintext highlighter-rouge">\</code>) at the end of the line, but not all Markdown applications support this, so it isn’t a great option from a compatibility perspective. And at least a couple lightweight markup languages don’t require anything at the end of the line — just type return and they’ll create a line break.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          First line with two spaces after. &nbsp;<br />
          And the next line.<br /><br />

          First line with the HTML tag after.&lt;br&gt;<br />
          And the next line.<br /><br />
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        First line with a backslash after.\<br />
        And the next line.<br /><br />

        First line with nothing after.<br />
        And the next line.<br /><br />
        </code>
      </td>
    </tr>
  </tbody>
</table>

<h2>Emphasis</h2>

<p>You can add emphasis by making text bold or italic.</p>

<h3 id="bold">Bold</h3>

<p>To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">I just love **bold text**.</code></td>
      <td><code class="highlighter-rouge">I just love &lt;strong&gt;bold text&lt;/strong&gt;.</code></td>
      <td>I just love <strong>bold text</strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">I just love __bold text__.</code></td>
      <td><code class="highlighter-rouge">I just love &lt;strong&gt;bold text&lt;/strong&gt;.</code></td>
      <td>I just love <strong>bold text</strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Love**is**bold</code></td> <td><code class="highlighter-rouge">Love&lt;strong&gt;is&lt;/strong&gt;bold</code></td>
      <td>Love<strong>is</strong>bold</td>
    </tr>
  </tbody>
</table>

<h4 id="bold-best-practices">Bold Best Practices</h4>

<p>Markdown applications don’t agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to bold the middle of a word for emphasis.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          Love**is**bold
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          Love__is__bold
        </code>
      </td>
    </tr>
  </tbody>
</table>

<h3 id="italic">Italic</h3>

<p>To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">Italicized text is the *cat's meow*.</code></td>
      <td><code class="highlighter-rouge">Italicized text is the &lt;em&gt;cat's meow&lt;/em&gt;.</code></td>
      <td>Italicized text is the <em>cat’s meow</em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Italicized text is the _cat's meow_.</code></td>
      <td><code class="highlighter-rouge">Italicized text is the &lt;em&gt;cat's meow&lt;/em&gt;.</code></td>
      <td>Italicized text is the <em>cat’s meow</em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">A*cat*meow</code></td>
      <td><code class="highlighter-rouge">A&lt;em&gt;cat&lt;/em&gt;meow</code></td>
      <td>A<em>cat</em>meow</td>
    </tr>
  </tbody>
</table>

<h4 id="italic-best-practices">Italic Best Practices</h4>

<p>Markdown applications don’t agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to italicize the middle of a word for emphasis.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          A*cat*meow
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          A_cat_meow
        </code>
      </td>
    </tr>
  </tbody>
</table>

<h3 id="bold-and-italic">Bold and Italic</h3>

<p>To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase. To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">This text is ***really important***.</code></td>
      <td><code class="highlighter-rouge">This text is &lt;strong&gt;&lt;em&gt;really important&lt;/em&gt;&lt;/strong&gt;.</code></td>
      <td>This text is <strong><em>really important</em></strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">This text is ___really important___.</code></td>
      <td><code class="highlighter-rouge">This text is &lt;strong&gt;&lt;em&gt;really important&lt;/em&gt;&lt;/strong&gt;.</code></td>
      <td>This text is <strong><em>really important</em></strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">This text is __*really important*__.</code></td>
      <td><code class="highlighter-rouge">This text is &lt;strong&gt;&lt;em&gt;really important&lt;/em&gt;&lt;/strong&gt;.</code></td>
      <td>This text is <strong><em>really important</em></strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">This text is **_really important_**.</code></td>
      <td><code class="highlighter-rouge">This text is &lt;strong&gt;&lt;em&gt;really important&lt;/em&gt;&lt;/strong&gt;.</code></td>
      <td>This text is <strong><em>really important</em></strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">This is really***very***important text.</code></td>
      <td><code class="highlighter-rouge">This is really&lt;strong&gt;&lt;em&gt;very&lt;/em&gt;&lt;/strong&gt;important text.</code></td>
      <td>This is really<strong><em>very</em></strong>important text.</td>
    </tr>
  </tbody>
</table>

<h4 id="bold-and-italic-best-practices">Bold and Italic Best Practices</h4>

<p>Markdown applications don’t agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to bold and italicize the middle of a word for emphasis.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          This is really***very***important text.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          This is really___very___important text.
        </code>
      </td>
    </tr>
  </tbody>
</table>

<h2>Blockquotes</h2>

<p>To create a blockquote, add a <code class="language-plaintext highlighter-rouge">&gt;</code> in front of a paragraph.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>&gt; Dorothy followed her through many of the beautiful rooms in her castle.
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<blockquote>
  <p>Dorothy followed her through many of the beautiful rooms in her castle.</p>
</blockquote>

<h3 id="blockquotes-with-multiple-paragraphs">Blockquotes with Multiple Paragraphs</h3>

<p>Blockquotes can contain multiple paragraphs. Add a <code class="language-plaintext highlighter-rouge">&gt;</code> on the blank lines between the paragraphs.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>&gt; Dorothy followed her through many of the beautiful rooms in her castle.
&gt;
&gt; The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<blockquote>
  <p>Dorothy followed her through many of the beautiful rooms in her castle.</p>

  <p>The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.</p>
</blockquote>

<h3 id="nested-blockquotes">Nested Blockquotes</h3>

<p>Blockquotes can be nested. Add a <code class="language-plaintext highlighter-rouge">&gt;&gt;</code> in front of the paragraph you want to nest.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>&gt; Dorothy followed her through many of the beautiful rooms in her castle.
&gt;
&gt;&gt; The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<blockquote>
  <p>Dorothy followed her through many of the beautiful rooms in her castle.</p>

  <blockquote>
    <p>The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.</p>
  </blockquote>
</blockquote>

<h3 id="blockquotes-with-other-elements">Blockquotes with Other Elements</h3>

<p>Blockquotes can contain other Markdown formatted elements. Not all elements can be used — you’ll need to experiment to see which ones work.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>&gt; #### The quarterly results look great!
&gt;
&gt; - Revenue was off the chart.
&gt; - Profits were higher than ever.
&gt;
&gt;  *Everything* is going according to **plan**.
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<blockquote>
  <h4 class="no-anchor">The quarterly results look great!</h4>

  <ul>
    <li>Revenue was off the chart.</li>
    <li>Profits were higher than ever.</li>
  </ul>

  <p><em>Everything</em> is going according to <strong>plan</strong>.</p>
</blockquote>

<h3 id="blockquotes-best-practices">Blockquotes Best Practices</h3>

<p>For compatibility, put blank lines before and after blockquotes.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
        Try to put a blank line before...<br /><br />

        &gt; This is a blockquote<br /><br />

        ...and after a blockquote.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        Without blank lines, this might not look right.<br />
        &gt; This is a blockquote<br />
        Don't do this!
        </code>
      </td>
    </tr>
  </tbody>
</table>

<h2>Lists</h2>

<p>You can organize items into ordered and unordered lists.</p>

<h3 id="ordered-lists">Ordered Lists</h3>

<p>To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
  <tr>
    <td>
      <code class="highlighter-rouge">
        1. First item<br />
        2. Second item<br />
        3. Third item<br />
        4. Fourth item
      </code>
    </td>
    <td>
      <code class="highlighter-rouge">
        &lt;ol&gt;<br />
          &lt;li&gt;First item&lt;/li&gt;<br />
          &lt;li&gt;Second item&lt;/li&gt;<br />
          &lt;li&gt;Third item&lt;/li&gt;<br />
          &lt;li&gt;Fourth item&lt;/li&gt;<br />
        &lt;/ol&gt;
      </code>
    </td>
    <td>
      <ol>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
        <li>Fourth item</li>
      </ol>
    </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          1. First item<br />
          1. Second item<br />
          1. Third item<br />
          1. Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ol&gt;<br />
            &lt;li&gt;First item&lt;/li&gt;<br />
            &lt;li&gt;Second item&lt;/li&gt;<br />
            &lt;li&gt;Third item&lt;/li&gt;<br />
            &lt;li&gt;Fourth item&lt;/li&gt;<br />
          &lt;/ol&gt;
        </code>
      </td>
      <td>
        <ol>
          <li>First item</li>
          <li>Second item</li>
          <li>Third item</li>
          <li>Fourth item</li>
        </ol>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          1. First item<br />
          8. Second item<br />
          3. Third item<br />
          5. Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ol&gt;<br />
            &lt;li&gt;First item&lt;/li&gt;<br />
            &lt;li&gt;Second item&lt;/li&gt;<br />
            &lt;li&gt;Third item&lt;/li&gt;<br />
            &lt;li&gt;Fourth item&lt;/li&gt;<br />
          &lt;/ol&gt;
        </code>
      </td>
      <td>
        <ol>
          <li>First item</li>
          <li>Second item</li>
          <li>Third item</li>
          <li>Fourth item</li>
        </ol>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          1. First item<br />
          2. Second item<br />
          3. Third item<br />
          &nbsp;&nbsp;&nbsp;&nbsp;1. Indented item<br />
          &nbsp;&nbsp;&nbsp;&nbsp;2. Indented item<br />
          4. Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ol&gt;<br />
            &lt;li&gt;First item&lt;/li&gt;<br />
            &lt;li&gt;Second item&lt;/li&gt;<br />
            &lt;li&gt;Third item<br />
              &lt;ol&gt;<br />
                &lt;li&gt;Indented item&lt;/li&gt;<br />
                &lt;li&gt;Indented item&lt;/li&gt;<br />
              &lt;/ol&gt;<br />
            &lt;/li&gt;<br />
            &lt;li&gt;Fourth item&lt;/li&gt;<br />
          &lt;/ol&gt;
        </code>
      </td>
      <td>
        <ol>
          <li>First item</li>
          <li>Second item</li>
          <li>Third item
            <ol>
              <li>Indented item</li>
              <li>Indented item</li>
            </ol>
          </li>
          <li>Fourth item</li>
        </ol>
      </td>
    </tr>
  </tbody>
</table>

<h4 id="ordered-list-best-practices">Ordered List Best Practices</h4>

<p>CommonMark and a few other lightweight markup languages let you use a parenthesis (<code class="language-plaintext highlighter-rouge">)</code>) as a delimiter (e.g., <code class="language-plaintext highlighter-rouge">1) First item</code>), but not all Markdown applications support this, so it isn’t a great option from a compatibility perspective. For compatibility, use periods only.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          1. First item<br />
          2. Second item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          1) First item<br />
          2) Second item
        </code>
      </td>
    </tr>
  </tbody>
</table>

<h3 id="unordered-lists">Unordered Lists</h3>

<p>To create an unordered list, add dashes (<code class="language-plaintext highlighter-rouge">-</code>), asterisks (<code class="language-plaintext highlighter-rouge">*</code>), or plus signs (<code class="language-plaintext highlighter-rouge">+</code>) in front of line items. Indent one or more items to create a nested list.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          - First item<br />
          - Second item<br />
          - Third item<br />
          - Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br />
            &lt;li&gt;First item&lt;/li&gt;<br />
            &lt;li&gt;Second item&lt;/li&gt;<br />
            &lt;li&gt;Third item&lt;/li&gt;<br />
            &lt;li&gt;Fourth item&lt;/li&gt;<br />
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>First item</li>
          <li>Second item</li>
          <li>Third item</li>
          <li>Fourth item</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          * First item<br />
          * Second item<br />
          * Third item<br />
          * Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br />
            &lt;li&gt;First item&lt;/li&gt;<br />
            &lt;li&gt;Second item&lt;/li&gt;<br />
            &lt;li&gt;Third item&lt;/li&gt;<br />
            &lt;li&gt;Fourth item&lt;/li&gt;<br />
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>First item</li>
          <li>Second item</li>
          <li>Third item</li>
          <li>Fourth item</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          + First item<br />
          + Second item<br />
          + Third item<br />
          + Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br />
            &lt;li&gt;First item&lt;/li&gt;<br />
            &lt;li&gt;Second item&lt;/li&gt;<br />
            &lt;li&gt;Third item&lt;/li&gt;<br />
            &lt;li&gt;Fourth item&lt;/li&gt;<br />
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>First item</li>
          <li>Second item</li>
          <li>Third item</li>
          <li>Fourth item</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          - First item<br />
          - Second item<br />
          - Third item<br />
          &nbsp;&nbsp;&nbsp;&nbsp;- Indented item<br />
          &nbsp;&nbsp;&nbsp;&nbsp;- Indented item<br />
          - Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br />
            &lt;li&gt;First item&lt;/li&gt;<br />
            &lt;li&gt;Second item&lt;/li&gt;<br />
            &lt;li&gt;Third item<br />
              &lt;ul&gt;<br />
                &lt;li&gt;Indented item&lt;/li&gt;<br />
                &lt;li&gt;Indented item&lt;/li&gt;<br />
              &lt;/ul&gt;<br />
            &lt;/li&gt;<br />
            &lt;li&gt;Fourth item&lt;/li&gt;<br />
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>First item</li>
          <li>Second item</li>
          <li>Third item
            <ul>
              <li>Indented item</li>
              <li>Indented item</li>
            </ul>
          </li>
          <li>Fourth item</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

<h4 id="starting-unordered-list-items-with-numbers">Starting Unordered List Items With Numbers</h4>

<p>If you need to start an unordered list item with a number followed by a period, you can use a backslash (<code class="language-plaintext highlighter-rouge">\</code>) to <a href="#escaping-characters">escape</a> the period.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          - 1968\. A great year!<br />
          - I think 1969 was second best.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br />
            &lt;li&gt;1968. A great year!&lt;/li&gt;<br />
            &lt;li&gt;I think 1969 was second best.&lt;/li&gt;<br />
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>1968. A great year!</li>
          <li>I think 1969 was second best.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

<h4 id="unordered-list-best-practices">Unordered List Best Practices</h4>

<p>Markdown applications don’t agree on how to handle different delimiters in the same list. For compatibility, don’t mix and match delimiters in the same list — pick one and stick with it.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          - First item<br />
          - Second item<br />
          - Third item<br />
          - Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          + First item<br />
          * Second item<br />
          - Third item<br />
          + Fourth item
        </code>
      </td>
    </tr>
  </tbody>
</table>

<h3 id="adding-elements-in-lists">Adding Elements in Lists</h3>

<p>To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples.</p>

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Tip:</strong> If things don't appear the way you expect, double check that you've indented the elements in the list four spaces or one tab.
</div>

<h4 id="paragraphs">Paragraphs</h4>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<ul>
  <li>This is the first list item.</li>
  <li>
    <p>Here’s the second list item.</p>

    <p>I need to add another paragraph below the second list item.</p>
  </li>
  <li>And here’s the third list item.</li>
</ul>

<h4 id="blockquotes">Blockquotes</h4>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>* This is the first list item.
* Here's the second list item.

    &gt; A blockquote would look great below the second list item.

* And here's the third list item.
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<ul>
  <li>This is the first list item.</li>
  <li>
    <p>Here’s the second list item.</p>

    <blockquote>
      <p>A blockquote would look great below the second list item.</p>
    </blockquote>
  </li>
  <li>And here’s the third list item.</li>
</ul>

<h4 id="code-blocks-1">Code Blocks</h4>

<p><a href="#code-blocks">Code blocks</a> are normally indented four spaces or one tab.  When they’re in a list, indent them eight spaces or two tabs.</p>

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>1. Open the file.
2. Find the following code block on line 21:

        &lt;html&gt;
          &lt;head&gt;
            &lt;title&gt;Test&lt;/title&gt;
          &lt;/head&gt;

3. Update the title to match the name of your website.
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<ol>
  <li>Open the file.</li>
  <li>
    <p>Find the following code block on line 21:</p>

    <div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code> &lt;html&gt;
   &lt;head&gt;
     &lt;title&gt;Test&lt;/title&gt;
   &lt;/head&gt;
</code></pre></div>    </div>
  </li>
  <li>Update the title to match the name of your website.</li>
</ol>

<h4 id="images">Images</h4>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3. Close the file.
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<ol>
  <li>Open the file containing the Linux mascot.</li>
  <li>
    <p>Marvel at its beauty.</p>

    <p><img src="https://d33wubrfki0l68.cloudfront.net/e7ed9fe4bafe46e275c807d63591f85f9ab246ba/e2d28/assets/images/tux.png" alt="Tux, the Linux mascot" /></p>
  </li>
  <li>Close the file.</li>
</ol>

<h4 id="lists">Lists</h4>

<p>You can nest an unordered list in an ordered list, or vice versa.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item
    <ul>
      <li>Indented item</li>
      <li>Indented item</li>
    </ul>
  </li>
  <li>Fourth item</li>
</ol>

<h2>Code</h2>

<p>To denote a word or phrase as code, enclose it in backticks (<code class="language-plaintext highlighter-rouge">`</code>).</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">At the command prompt, type `nano`.</code></td>
      <td><code class="highlighter-rouge">At the command prompt, type &lt;code&gt;nano&lt;/code&gt;. </code></td>
      <td>At the command prompt, type <code class="highlighter-rouge">nano</code>.</td>
    </tr>
  </tbody>
</table>

<h3 id="escaping-backticks">Escaping Backticks</h3>

<p>If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks (<code>``</code>).</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>``Use `code` in your Markdown file.``</code></td>
      <td><code class="highlighter-rouge">&lt;code&gt;Use `code` in your Markdown file.&lt;/code&gt;</code></td>
      <td><code>Use `code` in your Markdown file.</code></td>
    </tr>
  </tbody>
</table>

<h3 id="code-blocks">Code Blocks</h3>

<p>To create code blocks, indent every line of the block by at least four spaces or one tab.</p>

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>    &lt;html&gt;
      &lt;head&gt;
      &lt;/head&gt;
    &lt;/html&gt;
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<div class="language-text highlighter-rouge"><div class="highlight"><pre class="highlight"><code>&lt;html&gt;
  &lt;head&gt;
  &lt;/head&gt;
&lt;/html&gt;
</code></pre></div></div>

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Note:</strong> To create code blocks without indenting lines, use <a href="/extended-syntax/#fenced-code-blocks">fenced code blocks</a>.
</div>

<h2>Horizontal Rules</h2>

<p>To create a horizontal rule, use three or more asterisks (<code class="language-plaintext highlighter-rouge">***</code>), dashes (<code class="language-plaintext highlighter-rouge">---</code>), or underscores (<code class="language-plaintext highlighter-rouge">___</code>) on a line by themselves.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>***

---

_________________
</code></pre></div></div>

<p>The rendered output of all three looks identical:</p>

<hr />

<h3 id="horizontal-rule-best-practices">Horizontal Rule Best Practices</h3>

<p>For compatibility, put blank lines before and after horizontal rules.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
        Try to put a blank line before...<br /><br />

        ---<br /><br />

        ...and after a horizontal rule.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        Without blank lines, this would be a heading.<br />
        ---<br />
        Don't do this!
        </code>
      </td>
    </tr>
  </tbody>
</table>

<h2>Links</h2>

<p>To create a link, enclose the link text in brackets (e.g., <code class="language-plaintext highlighter-rouge">[Duck Duck Go]</code>) and then follow it immediately with the URL in parentheses (e.g., <code class="language-plaintext highlighter-rouge">(https://duckduckgo.com)</code>).</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<p>My favorite search engine is <a href="https://duckduckgo.com">Duck Duck Go</a>.</p>

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Note:</strong> To link to an element on the same page, see <a href="/extended-syntax/#linking-to-heading-ids">linking to heading IDs</a>.
</div>

<h3 id="adding-titles">Adding Titles</h3>

<p>You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<p>My favorite search engine is <a href="https://duckduckgo.com" title="The best search engine for privacy">Duck Duck Go</a>.</p>

<h3 id="urls-and-email-addresses">URLs and Email Addresses</h3>

<p>To quickly turn a URL or email address into a link, enclose it in angle brackets.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>&lt;https://www.markdownguide.org&gt;
&lt;fake@example.com&gt;
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<p><a href="https://www.markdownguide.org">https://www.markdownguide.org</a><br />
<a href="mailto:fake@example.com">fake@example.com</a></p>

<h3 id="formatting-links">Formatting Links</h3>

<p>To <a href="#emphasis">emphasize</a> links, add asterisks before and after the brackets and parentheses. To denote links as <a href="#code">code</a>, add backticks in the brackets.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<p>I love supporting the <strong><a href="https://eff.org">EFF</a></strong>.<br />
This is the <em><a href="https://www.markdownguide.org">Markdown Guide</a></em>.<br />
See the section on <a href="#code"><code class="language-plaintext highlighter-rouge">code</code></a>.</p>

<h3 id="reference-style-links">Reference-style Links</h3>

<p>Reference-style links are a special kind of link that make URLs easier to display and read in Markdown. Reference-style links are constructed in two parts: the part you keep inline with your text and the part you store somewhere else in the file to keep the text easy to read.</p>

<h4 id="formatting-the-first-part-of-the-link">Formatting the First Part of the Link</h4>

<p>The first part of a reference-style link is formatted with two sets of brackets. The first set of brackets surrounds the text that should appear linked. The second set of brackets displays a label used to point to the link you’re storing elsewhere in your document.</p>

<p>Although not required, you can include a space between the first and second set of brackets. The label in the second set of brackets is not case sensitive and can include letters, numbers, spaces, or punctuation.</p>

<p>This means the following example formats are roughly equivalent for the first part of the link:</p>

<ul>
  <li><code class="language-plaintext highlighter-rouge">[hobbit-hole][1]</code></li>
  <li><code class="language-plaintext highlighter-rouge">[hobbit-hole] [1]</code></li>
</ul>

<h4 id="formatting-the-second-part-of-the-link">Formatting the Second Part of the Link</h4>

<p>The second part of a reference-style link is formatted with the following attributes:</p>

<ol>
  <li>The label, in brackets, followed immediately by a colon and at least one space (e.g., <code class="language-plaintext highlighter-rouge">[label]: </code>).</li>
  <li>The URL for the link, which you can optionally enclose in angle brackets.</li>
  <li>The optional title for the link, which you can enclose in double quotes, single quotes, or parentheses.</li>
</ol>

<p>This means the following example formats are all roughly equivalent for the second part of the link:</p>

<ul>
  <li><code class="language-plaintext highlighter-rouge">[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle</code></li>
  <li><code class="language-plaintext highlighter-rouge">[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"</code></li>
  <li><code class="language-plaintext highlighter-rouge">[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'</code></li>
  <li><code class="language-plaintext highlighter-rouge">[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)</code></li>
  <li><code class="language-plaintext highlighter-rouge">[1]: &lt;https://en.wikipedia.org/wiki/Hobbit#Lifestyle&gt; "Hobbit lifestyles"</code></li>
  <li><code class="language-plaintext highlighter-rouge">[1]: &lt;https://en.wikipedia.org/wiki/Hobbit#Lifestyle&gt; 'Hobbit lifestyles'</code></li>
  <li><code class="language-plaintext highlighter-rouge">[1]: &lt;https://en.wikipedia.org/wiki/Hobbit#Lifestyle&gt; (Hobbit lifestyles)</code></li>
</ul>

<p>You can place this second part of the link anywhere in your Markdown document. Some people place them immediately after the paragraph in which they appear while other people place them at the end of the document (like endnotes or footnotes).</p>

<h4 id="an-example-putting-the-parts-together">An Example Putting the Parts Together</h4>

<p>Say you add a URL as a <a href="#links">standard URL link</a> to a paragraph and it looks like this in Markdown:</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.
</code></pre></div></div>

<p>Though it may point to interesting additional information, the URL as displayed really doesn’t add much to the existing raw text other than making it harder to read. To fix that, you could format the URL like this instead:</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: &lt;https://en.wikipedia.org/wiki/Hobbit#Lifestyle&gt; "Hobbit lifestyles"
</code></pre></div></div>

<p>In both instances above, the rendered output would be identical:</p>

<blockquote>
  <p>In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to  eat: it was a <a href="https://en.wikipedia.org/wiki/Hobbit#Lifestyle" title="Hobbit lifestyles">hobbit-hole</a>, and that means comfort.</p>
</blockquote>

<p>and the HTML for the link would be:</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>&lt;a href="https://en.wikipedia.org/wiki/Hobbit#Lifestyle" title="Hobbit lifestyles"&gt;hobbit-hole&lt;/a&gt;
</code></pre></div></div>

<h3 id="link-best-practices">Link Best Practices</h3>

<p>Markdown applications don’t agree on how to handle spaces in the middle of a URL. For compatibility, try to URL encode any spaces with <code class="language-plaintext highlighter-rouge">%20</code>.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
        [link](https://www.example.com/my%20great%20page)
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        [link](https://www.example.com/my great page)
        </code>
      </td>
    </tr>
  </tbody>
</table>

<h2>Images</h2>

<p>To add an image, add an exclamation mark (<code class="language-plaintext highlighter-rouge">!</code>), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title after the URL in the parentheses.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<p><img srcset="https://mdg.imgix.net/assets/images/san-juan-mountains.jpg?auto=format&amp;fit=clip&amp;w=480 480w,              https://mdg.imgix.net/assets/images/san-juan-mountains.jpg?auto=format&amp;fit=clip&amp;q=40&amp;w=1080 1080w" src="https://mdg.imgix.net/assets/images/san-juan-mountains.jpg" class="img-fluid" title="San Juan Mountains" alt="The San Juan Mountains are beautiful!" loading="lazy" sizes="100vw" /></p>

<h3 id="linking-images">Linking Images</h3>

<p>To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<div>
  <a href="https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv" class="no-underline">

<img srcset="https://mdg.imgix.net/assets/images/shiprock.jpg?auto=format&amp;fit=clip&amp;w=480 480w,
             https://mdg.imgix.net/assets/images/shiprock.jpg?auto=format&amp;fit=clip&amp;q=40&amp;w=1080 1080w" src="https://mdg.imgix.net/assets/images/shiprock.jpg" class="img-fluid" title="Shiprock, New Mexico by Beau Rogers" alt="An old rock in the desert" loading="lazy" sizes="100vw" />

  </a>
</div>

<h2>Escaping Characters</h2>

<p>To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (<code class="language-plaintext highlighter-rouge">\</code>) in front of the character.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>\* Without the backslash, this would be a bullet in an unordered list.
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<p>* Without the backslash, this would be a bullet in an unordered list.</p>

<h3 id="characters-you-can-escape">Characters You Can Escape</h3>

<p>You can use a backslash to escape the following characters.</p>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Character</th>
      <th>Name</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>\</td>
      <td>backslash</td>
    </tr>
    <tr>
      <td>`</td>
      <td>backtick (see also <a href="#escaping-backticks">escaping backticks in code</a>)</td>
    </tr>
    <tr>
      <td>*</td>
      <td>asterisk</td>
    </tr>
    <tr>
      <td>_</td>
      <td>underscore</td>
    </tr>
    <tr>
      <td>{ }</td>
      <td>curly braces</td>
    </tr>
    <tr>
      <td>[ ]</td>
      <td>brackets</td>
    </tr>
    <tr>
      <td>&lt; &gt;</td>
      <td>angle brackets</td>
    </tr>
    <tr>
      <td>( )</td>
      <td>parentheses</td>
    </tr>
    <tr>
      <td>#</td>
      <td>pound sign</td>
    </tr>
    <tr>
      <td>+</td>
      <td>plus sign</td>
    </tr>
    <tr>
      <td>-</td>
      <td>minus sign (hyphen)</td>
    </tr>
    <tr>
      <td>.</td>
      <td>dot</td>
    </tr>
    <tr>
      <td>!</td>
      <td>exclamation mark</td>
    </tr>
    <tr>
      <td>|</td>
      <td>pipe (see also <a href="/extended-syntax/#escaping-pipe-characters-in-tables">escaping pipe in tables</a>)</td>
    </tr>
  </tbody>
</table>

<h2>HTML</h2>

<p>Many Markdown applications allow you to use HTML tags in Markdown-formatted text. This is helpful if you prefer certain HTML tags to Markdown syntax. For example, some people find it easier to use HTML tags for images. Using HTML is also helpful when you need to change the attributes of an element, like specifying the color of text or changing the width of an image.</p>

<p>To use HTML, place the tags in the text of your Markdown-formatted file.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>This **word** is bold. This &lt;em&gt;word&lt;/em&gt; is italic.
</code></pre></div></div>

<p>The rendered output looks like this:</p>

<p>This <strong>word</strong> is bold. This <em>word</em> is italic.</p>

<h3 id="html-best-practices">HTML Best Practices</h3>

<p>For security reasons, not all Markdown applications support HTML in Markdown documents. When in doubt, check your Markdown application’s documentation. Some applications support only a subset of HTML tags.</p>

<p>Use blank lines to separate block-level HTML elements like <code class="language-plaintext highlighter-rouge">&lt;div&gt;</code>, <code class="language-plaintext highlighter-rouge">&lt;table&gt;</code>, <code class="language-plaintext highlighter-rouge">&lt;pre&gt;</code>, and <code class="language-plaintext highlighter-rouge">&lt;p&gt;</code> from the surrounding content. Try not to indent the tags with tabs or spaces — that can interfere with the formatting.</p>

<p>You can’t use Markdown syntax inside block-level HTML tags. For example, <code class="language-plaintext highlighter-rouge">&lt;p&gt;italic and **bold**&lt;/p&gt;</code> won’t work.</p>



        </div>
        <div class="col-md-3 d-none d-md-block" id="sidebar">
          <nav id="toc" data-toggle="toc" class="sticky-top" style="z-index:1"></nav>

          <div style="position: fixed; bottom: 0px; right: 0px;">
            <div data-ea-publisher="markdownguide" data-ea-type="image"></div>
          </div>

        </div>
      </div>
    </div>

<script type='text/javascript' src='https://d33wubrfki0l68.cloudfront.net/js/0c3170eb96147081322d4121731a6c6dfdc772cb/assets/javascript/anchor.min.js'></script>
<script>
  anchors.options = {
  placement: 'right',
  };
  anchors.add('h1, h2, h3, h4, h5').remove('.no-anchor');
</script>

<!-- for search -->
<script src='https://d33wubrfki0l68.cloudfront.net/js/a5cab668546809f89ffe5d38243d7a3cb47e4b05/assets/javascript/docsearch.min.js'></script>
<script>
docsearch({
apiKey: '0125ba824e95b21d36ae268518067391',
indexName: 'markdownguide',
inputSelector: '#search-input',
debug: false // Set debug to true if you want to inspect the dropdown
});
</script>

  </body>
</html>

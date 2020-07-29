---
title: Lint Rule html/preferClosingNonVoid
layout: layouts/page.njk
showHero: false
description: MISSING DOCUMENTATION
eleventyNavigation:
  key: lint-rules/html/preferClosingNonVoid
  parent: lint-rules
  title: html/preferClosingNonVoid
---

# html/preferClosingNonVoid

MISSING DOCUMENTATION

<!-- EVERYTHING BELOW IS AUTOGENERATED. SEE SCRIPTS FOLDER FOR UPDATE SCRIPTS hash(fa88da292e3cb134d96de5a194cffad822ebaebf) -->

## Examples
### Invalid
<pre class="language-text"><code class="language-text"><span class="token punctuation">&lt;</span><span class="token attr-name">div</span> <span class="token punctuation">/&gt;</span></code></pre>
<pre class="language-text"><code class="language-text">
 <span style="text-decoration-style: dotted;">filename.html:1</span> <strong>lint/html/preferClosingNonVoid</strong> <span style="color: white; background-color: #ddd;"> FIXABLE </span> ━━━━━━━━━━━━━━━━━

  <strong><span style="color: Tomato;">✖ </span></strong><span style="color: Tomato;">Non-void HTML elements cannot be self-closing. This is valid when</span>
    <span style="color: Tomato;">using JSX, but not when using HTML.</span>

    <span class="token punctuation">&lt;</span><span class="token attr-name">div</span> <span class="token punctuation">/&gt;</span>
    <span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span>

  <strong><span style="color: DodgerBlue;">ℹ </span></strong><span style="color: DodgerBlue;">Recommended fix</span>

  <strong>  </strong><strong>1</strong><strong> </strong><strong> </strong><strong> │ </strong><span style="color: Tomato;">-</span> <span style="color: Tomato;">&lt;div</span><span style="color: Tomato;"><strong><span style="opacity: 0.8;">&middot;</span>"</strong></span><span style="color: Tomato;">/&gt;</span>
  <strong>  </strong><strong> </strong><strong> </strong><strong>1</strong><strong> │ </strong><span style="color: MediumSeaGreen;">+</span> <span style="color: MediumSeaGreen;">&lt;div</span><span style="color: MediumSeaGreen;"><strong>&gt;</strong></span>
  <strong>  </strong><strong> </strong><strong> </strong><strong>2</strong><strong> │ </strong><span style="color: MediumSeaGreen;">+</span> <span style="color: MediumSeaGreen;"><strong>&lt;</strong></span><span style="color: MediumSeaGreen;">/</span><span style="color: MediumSeaGreen;"><strong>div</strong></span><span style="color: MediumSeaGreen;">&gt;</span>

</code></pre>
### Valid
<pre class="language-text"><code class="language-text"><span class="token punctuation">&lt;</span><span class="token attr-name">div</span><span class="token punctuation">&gt;</span><span class="token punctuation">&lt;/</span><span class="token attr-name">div</span><span class="token punctuation">&gt;</span></code></pre>
<pre class="language-text"><code class="language-text"><span class="token punctuation">&lt;</span><span class="token attr-name">div</span><span class="token punctuation">&gt;</span>child<span class="token punctuation">&lt;/</span><span class="token attr-name">div</span><span class="token punctuation">&gt;</span></code></pre>
<pre class="language-text"><code class="language-text"><span class="token punctuation">&lt;</span><span class="token attr-name">input</span><span class="token punctuation">&gt;</span></code></pre>
<pre class="language-text"><code class="language-text"><span class="token punctuation">&lt;</span><span class="token attr-name">input</span> <span class="token punctuation">/&gt;</span></code></pre>
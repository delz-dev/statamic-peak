<template><h1 id="contributing" tabindex="-1"><a class="header-anchor" href="#contributing" aria-hidden="true">#</a> Contributing</h1>
<p>Contributions and discussions are always welcome, no matter how large or small. Treat each other with respect. Read the <a href="https://github.com/studio1902/statamic-peak/blob/main/.github/CODE_OF_CONDUCT.md" target="_blank" rel="noopener noreferrer">Code of Conduct<OutboundLink/></a>.</p>
<p>Statamic Peak is a mono repo containing both a development environment and the docs.</p>
<h2 id="repo-structure" tabindex="-1"><a class="header-anchor" href="#repo-structure" aria-hidden="true">#</a> Repo structure</h2>
<table>
<thead>
<tr>
<th>Location</th>
<th>Purpose</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>/</code></td>
<td>The root level contains the actual kit that gets installed by Statamic.</td>
</tr>
<tr>
<td><code>/docs/</code></td>
<td>The documentation auto deployed to <a href="https://peak.studio1902.nl" target="_blank" rel="noopener noreferrer">peak.studio1902.nl<OutboundLink/></a> running on Netlify.</td>
</tr>
<tr>
<td><code>/dev/</code></td>
<td>The actual development environment. A running Statamic Peak instance.</td>
</tr>
</tbody>
</table>
<h2 id="development-environment" tabindex="-1"><a class="header-anchor" href="#development-environment" aria-hidden="true">#</a> Development environment</h2>
<p>If you want to contribute to the core Starter Kit make sure you target files the <code>/dev/</code> folder and run your local install from this folder. When you use valet you can navigate to the folder and type: <code>valet link statamic-peak</code>.</p>
<h2 id="docs" tabindex="-1"><a class="header-anchor" href="#docs" aria-hidden="true">#</a> Docs</h2>
<p>The documentation run on https://vuepress.vuejs.org. To locally install this navigate to the <code>docs</code> dir in this repo and:</p>
<ol>
<li><code>npm i</code></li>
<li><code>npm run docs:dev</code></li>
<li>Visit http://localhost:8080.</li>
</ol>
<p>Commits to these docs are automatically deployed to production on https://peak.studio1902.nl using <a href="https://netlify.com" target="_blank" rel="noopener noreferrer">Netlify<OutboundLink/></a>.</p>
<h2 id="thanks" tabindex="-1"><a class="header-anchor" href="#thanks" aria-hidden="true">#</a> Thanks</h2>
<p>These docs are initially setup using VuePress 1 by <a href="https://github.com/robertguss/" target="_blank" rel="noopener noreferrer">Robert Guss<OutboundLink/></a>. Thank you so much! Today we run VuePress 2.</p>
</template>

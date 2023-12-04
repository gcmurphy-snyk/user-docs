# Supported languages, frameworks, and feature availability overview

Get an overview of supported languages and package managers across Snyk environments, including feature availability for open source and licensing (Snyk Open Source) and code analysis (Snyk Code).

## Open source and licensing (Snyk Open Source)

The following table lists the programming languages, fully supported package managers, and features for Snyk Open Source.

{% hint style="info" %}
Before scanning your Open Source Project for vulnerabilities, with limited exceptions, you must **build your Project**. For details, see [Which Projects must be built before testing with CLI?](https://support.snyk.io/hc/en-us/articles/360015552617-Which-projects-must-be-built-before-testing-with-CLI-)
{% endhint %}

{% hint style="info" %}
The tables below are scrollable right and left. Ensure you check all available columns.
{% endhint %}

<table data-full-width="false"><thead><tr><th width="135">Ecosystem</th><th width="192" align="center">Import your app through SCM</th><th width="173" align="center">Test or monitor your app through CLI and IDE</th><th width="149" align="center">Test your app through SBOM</th><th width="148" align="center">Test your app's packages </th><th width="149">Features</th><th width="178">Package manager versions</th></tr></thead><tbody><tr><td><p><a href=".net/"><strong>.NET</strong></a><br></p><p><strong>NuGet</strong></p><p><strong>Paket</strong></p></td><td align="center">NuGet</td><td align="center"><strong>✔︎</strong></td><td align="center"><p><strong>✔︎</strong> </p><p>pkg:nuget</p></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:nuget</p></td><td><ul><li>Fix PRs (NuGet)</li><li>License scanning</li><li>Reports</li></ul></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td></tr><tr><td><a href="c-c++.md#open-source-and-licensing"><strong>C/C++</strong></a></td><td align="center"><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td><td align="center"><strong>✔︎</strong></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:generic</p></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:generic</p></td><td><ul><li>License scanning</li></ul><ul><li>Reports</li></ul></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td></tr><tr><td><p><a href="../../scan-using-snyk/supported-languages-and-frameworks/dart.md"><strong>Dart</strong></a><br></p><p><strong>Pub</strong></p></td><td align="center"><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td><td align="center"><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td><td align="center"><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:pub</p></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td></tr><tr><td><p><a href="../../scan-using-snyk/supported-languages-and-frameworks/elixir.md"><strong>Elixir</strong></a><br></p><p><strong>Hex</strong></p></td><td align="center"><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td><td align="center"><strong>✔︎</strong></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:hex</p></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:hex</p></td><td><ul><li>License scanning</li></ul><ul><li>Reports</li></ul></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td></tr><tr><td><p><a href="go.md#open-source-and-licensing"><strong>Go</strong></a><br></p><p><strong>Go Modules</strong></p><p><strong>dep</strong></p></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:golang</p></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:golang</p></td><td><ul><li>License scanning</li></ul><ul><li>Reports</li></ul></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td></tr><tr><td><p><a href="java-and-kotlin.md#open-source-and-licensing"><strong>Java and Kotlin</strong></a><br></p><p><strong>Maven</strong></p><p><strong>Gradle</strong></p></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:maven</p></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:maven</p></td><td><ul><li>Fix PRs (Maven)</li></ul><ul><li>License scanning</li></ul><ul><li>Reports</li></ul></td><td><p></p><p>Maven</p><ul><li><code>3.*</code> For details, see the <a href="https://github.com/snyk/snyk-mvn-plugin#support">Snyk Maven plugin readme</a>.</li></ul><p>Gradle</p><ul><li><code>4.*</code>, <code>5.*</code>, <code>6.*</code>, <code>7.*</code> <br>For more information, see the <a href="https://github.com/snyk/snyk-gradle-plugin#support">Snyk Gradle plugin readme</a>.</li></ul></td></tr><tr><td><p><a href="javascript.md#open-source-and-licensing"><strong>JavaScript</strong></a><br></p><p><strong>npm</strong></p><p><strong>Yarn</strong></p></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:npm</p></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:npm</p></td><td><ul><li>Fix PRs</li></ul><ul><li>License scanning</li></ul><ul><li>Reports</li></ul></td><td><p></p><p>npm</p><ul><li><code>Lockfile 1, Lockfile 2, Lockfile 3, 7.*</code> <br>For details, see the <a href="javascript.md#npm">Snyk Javascript </a>page.</li></ul><p>Yarn</p><ul><li><code>Yarn 1, Yarn 2, Yarn 3</code>. For more information, see the <a href="javascript.md#yarn">Snyk Javascript </a>page.</li></ul></td></tr><tr><td><p><a href="php.md#open-source-and-licensing"><strong>PHP</strong></a><br></p><p><strong>Composer</strong></p></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:composer</p></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:composer</p></td><td><ul><li>License scanning</li></ul><ul><li>Reports</li></ul></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td></tr><tr><td><p><a href="python.md#open-source-and-licensing"><strong>Python</strong></a><br></p><p><strong>Pip</strong></p><p><strong>Poetry</strong></p><p><strong>pipenv</strong></p><p><strong>setup.py</strong></p></td><td align="center">Pip and Poetry</td><td align="center"><strong>✔︎</strong></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:pypi</p></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:pypi</p></td><td><ul><li>Fix PRs (Pip)</li></ul><ul><li>License scanning</li></ul><ul><li>Reports</li></ul></td><td>Suitable with <code>Python 2 -> 2.7.16</code>, and <code>Python  3 -> 3.7.4</code>.</td></tr><tr><td><p><a href="ruby.md#open-source-and-licensing"><strong>Ruby</strong></a><br></p><p><strong>Bundler</strong></p></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:gem</p></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:gem</p></td><td><ul><li>Fix PRs</li></ul><ul><li>License scanning</li></ul><ul><li>Reports</li></ul></td><td>All Gemfile and Gemfile.lock compatible with the <a href="ruby.md#supported-ruby-versions">Snyk supported Ruby versions</a>. </td></tr><tr><td><p><a href="../../scan-using-snyk/supported-languages-and-frameworks/rust.md"><strong>Rust</strong></a><br></p><p><strong>Cargo</strong></p></td><td align="center"><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td><td align="center"><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:cargo</p></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:cargo</p></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td></tr><tr><td><p><a href="scala.md#open-source-and-licensing"><strong>Scala</strong></a><br></p><p><strong>sbt</strong></p></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:maven</p></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:maven</p></td><td><ul><li>License scanning</li></ul><ul><li>Reports</li></ul></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2796">➖</span></td></tr><tr><td><p><a href="swift-and-objective-c.md#open-source-and-licensing"><strong>Swift and Objective-C</strong></a><br></p><p><strong>CocoaPods</strong></p><p><strong>Swift Package Manager</strong></p></td><td align="center">CocoaPods</td><td align="center"><strong>✔︎</strong></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:swift<br>pkg:cocoapods</p></td><td align="center"><p><strong>✔︎</strong></p><p>pkg:swift<br>pkg:cocoapods</p></td><td><ul><li>License scanning (CocoaPods)</li></ul><ul><li>Reports</li></ul></td><td><p></p><p>CocoaPods</p><ul><li>Swift Package Manager</li></ul><ul><li><code>Swift v3.0</code> or higher.</li></ul></td></tr></tbody></table>

## Code analysis (Snyk Code)

The following table lists the programming languages and fully supported frameworks and features for Snyk Code.

<table data-full-width="false"><thead><tr><th width="232">Language and framework</th><th width="131" align="center">Git integration (SCM)</th><th width="207" align="center">Snyk CLI, plugins (IDE), CI/CD</th><th>Features</th></tr></thead><tbody><tr><td><strong>Apex</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><ul><li>Reports</li><li>Custom rules</li></ul></td></tr><tr><td><p><strong>C#</strong></p><ul><li><strong>.NET</strong></li><li><strong>ASP.NET</strong></li><li><strong>.NET Core</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><p><a href="c-c++.md"><strong>C/C++</strong></a> <strong>(beta)</strong></p><ul><li><strong>C++ Standard Library</strong></li><li><strong>POSIX</strong></li><li><strong>Win32</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td>Reports</td></tr><tr><td><strong>Go</strong></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><p><a href="java-and-kotlin.md"><strong>Java</strong></a></p><ul><li><strong>Apache Camel</strong></li><li><strong>Apache Struts</strong></li><li><strong>Spring MVC</strong></li><li><strong>Spring JDBC</strong></li><li><strong>Jakarta XML Services</strong></li><li><strong>Dropwizard</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><p><a href="javascript.md"><strong>JavaScript</strong></a></p><ul><li><strong>React</strong></li><li><strong>Vue.js</strong></li><li><strong>Express</strong></li><li><strong>JQuery</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><a href="java-and-kotlin.md"><strong>Kotlin</strong></a> </td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td>Reports</td></tr><tr><td><p><strong>PHP</strong></p><ul><li><strong>Symfony</strong></li><li><strong>Laravel</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><p><a href="python.md"><strong>Python</strong></a></p><ul><li><strong>Django</strong></li><li><strong>Flask</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><p><a href="ruby.md"><strong>Ruby</strong></a></p><ul><li><strong>Ruby On Rails</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><p><a href="scala.md"><strong>Scala</strong></a> </p><ul><li><strong>Play</strong></li><li><strong>Akka</strong></li><li><strong>HTTP4S</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td>Reports</td></tr><tr><td><p><a href="swift-and-objective-c.md"><strong>Swift</strong></a> </p><ul><li><strong>AlamoFire</strong></li><li><strong>Pathos</strong></li><li><strong>SQLite</strong></li><li><strong>CryptoKit</strong></li></ul></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td>Reports</td></tr><tr><td><a href="../../scan-using-snyk/supported-languages-and-frameworks/typescript.md"><strong>TypeScript</strong></a></td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td><ul><li>Reports</li></ul><ul><li>Custom rules</li></ul></td></tr><tr><td><a href="../../scan-using-snyk/supported-languages-and-frameworks/vb.net.md"><strong>VB.NET</strong></a> </td><td align="center"><strong>✔︎</strong></td><td align="center"><strong>✔︎</strong></td><td>Reports</td></tr></tbody></table>
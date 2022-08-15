[![The Quark banner](https://raw.githubusercontent.com/anafro/anafro/main/Banners/Quark.svg "Quark is still in development. You can't download it yet.")]()

<!--(https://sakurator.anafro.ru/)-->

<h1 align="center">
  <br>
  <a href="https://anafro.ru/quark"><img src="https://raw.githubusercontent.com/anafro/anafro/main/Logos/Quark.svg" alt="Quark Logo" width="200"></a>
  
  <br>
  Anafro Quark 
  <br>

  <h4 align="center">A small, but powerful database management system with beautiful Excel-like interface.</h4>

  <p align="center">
  <a href="#what-is-it">What Is It?</a> •
  <a href="#features">Features</a> •
  <a href="#development-status">Development status</a> •
  Download <em>(not available yet)</em> •
  <a href="#as-portfolio">Quark as a Portfolio Project</a> •
  <a href="#documentation">Documentation</a> •
  <a href="#license">License</a>
</p>
</h1>

<hr/>
<br/>

<h2 id="what-is-it" align="center">What is it?</h2>
Anafro Quark is a database management system with 3 programs inside: Quark Server, Quark Studio, and Quark Console. Quark uses its own query language - Quark QL.

* **Quark Server** is a software that handles the databases and tables in it according the queries that it receives.
* **Quark Studio** is a desktop client that can connect to any Quark Server in the Internet and send queries to them. It also has a handful Quark QL editor and a table editor that looks like Excel.
* **Quark Console** is a CLI that has less functionality than Quark Studio, but it is super-handy when you need to send a query fast or debug your server.

<hr>

<h2 id="features" align="center">Features</h2>
<br>

<h2 align="center">
    <img src="https://raw.githubusercontent.com/anafro/anafro/main/Banners/Quark.Features.png" alt="Markdownify">
</h2>

Despide the fact that Quark can not be compared with DBMS giants such as MySQL yet, Quark can offer you features that other database management systems don't have.

* Quark has its own query language called Quark QL, which is really similar to Python. You can use useful functions inside your queries, e.g. `@upper('text')` will become to `TEXT`. 
* Quark QL contains almost 100 instructions, so the flexibility of database management becomes really cool!
* Quark QL also contains build-in boilerplate column types, such as `email`, `nickname` and `password`. Not needed to remember all type modifiers anymore!
* Quark Server can handle thousands of connections at once.
* It's not required to have any programming or database management experience to use Quark! You can always switch to table editor mode and edit your tables as you get used to in Excel.
* Quark Server has some type filters for your columns. For example, you have a `money` column that obviously must not be less than zero. You can apply a filter `@not negative` (but we also have a `@money` type so yeah).

<hr>

<h2 id="features" align="center">Development status</h2>
<br>

<h2 align="center">
    <img src="https://raw.githubusercontent.com/anafro/anafro/main/Banners/Quark.Progress.png" alt="Markdownify">
</h2>

Development of Quark is still ongoing! The scheduled release date of all Quark products is the end of September.

<hr>

<h2 id="as-portfolio" align="center">Quark as a Portfolio Project</h2>
<br>

Quark is a huge software system that contains 4 programs (I include Quark Installer, because it's also written from zero). There's a table of technologies used in Quark:

| Software        | Language used                        | Libraries or frameworks used        | Other technologies used    | Repository                                                   |
|-----------------|--------------------------------------|-------------------------------------|----------------------------|--------------------------------------------------------------|
| Quark Server    | Java                                 | Netty, Java AWT, Java Swing         | Maven                      | <a href="https://github.com/anafro/quark-server">Open</a>    |
| Quark Console   | Python                               | Rich                                | (none)                     | <a href="https://github.com/anafro/quark-console">Open</a>   |
| Quark Studio    | _C# or JavaScript (not decided yet)_ | _WPF or Electron (not decided yet)_ | npm if JavaScript was used | <a href="https://github.com/anafro/quark-studio">Open</a>    |
| Quark Installer | C#                                   | WPF                                 | (none)                     | <a href="https://github.com/anafro/quark-installer">Open</a> |
| Quark ORM       | TypeScript                           | n/a                                 | n/a                        | <a href="https://github.com/anafro/quark-orm">Open</a>       |
| Quark API       | TypeScript and (probably) C#         | n/a                                 | n/a                        | <a href="https://github.com/anafro/quark-api">Open</a>       |

You _~~can~~_ will be able to check out all the repositories of Quark programs above.

<hr>

<h2 id="documentation" align="center">Documentation</h2>
<br>

Documentation of Quark QL and Quark Server Plugin API will appear on corresponding GitHub repositories soon.

<hr>

<h2 id="license" align="center">License</h2>
<br>

All the Quark programs are licensed under MIT. Use can find the license document inside each GitHub repository of Quark program.
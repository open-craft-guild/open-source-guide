---
locale: uk-UA
title: Початок Open Source проекту
description: Дізнайтесь більше про світ open source та будьте готові до запуску власного проекту.
class: beginners
toc:
  Що-таке-open-source-та-навіщо-він-потрібен: "Що таке open source та навіщо він потрібен"
  Чи-слід-мені-запускати-власний-open-source-проект: "Чи слід мені запускати власний open source проект?"
  Запуск-вашого-власного-open-source-проекту: "Запуск вашого власного open source проекту"
  Назва-та-бренд-вашого-проекту: "Назва та бренд вашого проекту"
  Ваш-передстартовий-контрольний-список: "Ваш передстартовий контрольний список"
order: 2
image: /assets/images/cards/beginner.png
---

## Що таке open source та навіщо він потрібен

Отже ви роздумуєте над початком роботи з open source? Вітаємо! Світ цінує ваш внесок. Давайте поговоримо про те, що таке open source та чому люди цим займаються.

### Шо означає "open source"?

Коли проект є open source, то це означає, що **будь-хто може переглядати, використовувати, змінювати та поширювати ваш проект з будь-якою метою.** Ці дозволи забезпечуються [open source ліцензією](https://opensource.org/licenses).

Open source є потужним, бо він знижує перешкоди на шляху впровадження, дозволяючи ідеям поширюватись швидше.

Щоб зрозуміти як це працює, уявіть, що ви принесли вишневий пиріг, щоб почастувати своїх друзів на товариській вечірці.

* Кожен пробує пиріг (_використання_)
* Пиріг стає хітом! Друзі просять у вас рецепт і ви його даєте (_перегляд_)
* Один з друзів, кондитер, пропонує зменшити кількість цукру (_зміна_)
* Інший товариш просить дозволу використати це для обіду на наступному тижні (_поширення_)

Для порівняння, цей процес з closed source проектом виглядав би як похід у ресторан та замовлення шматочку вишневого пирога. Ви маєте платити за те щоб скуштувати пирога і ресторан навряд чи дасть вам свій рецепт. Якщо ви повністю скопіювали їхній пиріг і продали його під своїм іменем, то ресторан може вжити заходів проти вас.

### Чому люди роблять свою роботу open source?

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/1500684?v=3&s=460" class="pquote-avatar" alt="avatar">
  Однією з найкорисніших речей у плані набутого досвіду, що я отримав від використання та співпраці в open source, стали взамємовідносини з іншими розробниками, які стикаються з тими ж проблемами що й я.
  <p markdown="1" class="pquote-credit">
— @kentcdodds, ["How getting into Open Source has been awesome for me"](https://medium.com/@kentcdodds/how-getting-into-open-source-has-been-awesome-for-me-8480cd756a80#.pjt9oqp4w)
  </p>
</aside>

[Існує чимало причин](http://ben.balter.com/2015/11/23/why-open-source/), через які особа чи організація можуть захотіти зробити свій проект open source. Ось деякі приклади:

* **Співпраця:** Open source проекти можуть приймати зміни від будь-кого у світі. Наприклад, [Exercism](https://github.com/exercism/), це платформа для вправляння у програмуванні з більш, ніж 350 учасниками.

* **Запозичення та переосмислення:** Open source проекти можуть бути використані будь-ким і майже з будь-якою метою. Люди можуть навіть використовувати ці проекти для побудови інших. Наприклад, [WordPress](https://github.com/WordPress), був створений як відгалуження існуючого проекту під назвою [b2](https://github.com/WordPress/book/blob/master/Content/Part%201/2-b2-cafelog.md).

* **Прозорість:** Кожен може оглядати open source проект для пошуку помилок чи невідповідностей. Прозорість має значання для урядів таких країн, як от [Болгарія](https://medium.com/@bozhobg/bulgaria-got-a-law-requiring-open-source-98bf626cf70a) чи [Сполучені Штати Америки](https://sourcecode.cio.gov/), регульованих галузей на кшталт банківської сфери та охорони здоров’я, або програмного забезпечення для безпеки на зразок [Let's Encrypt](https://github.com/letsencrypt).

Варто зазначити, що Open source це не тільки для програмного забезпечення. Ви можете зробити open source усе що завгодно, від наборів даних до книжок. Ознайомтесь з [GitHub Explore](https://github.com/explore) для ідей щодо того, що ще ви можете зробити open source.

### Чи означає open source — "безкоштовно"?

Одна з найбільших принад open source полягає у тому, що це не коштує грошей. Втім, "безкоштовність" є побічним продуктом загальної вартості open source.

Через те, що [open source ліцензія вимагає](https://opensource.org/osd-annotated) щоб кожен міг використовувати, змінювати та ділитись вашим проектом з довільними намірами, проекти, як правило, є безкоштовними. Якщо проект коштує грошей, то будь-хто може легально зробити його копію та користуватись цією безкоштовною версію.

В результаті, більшість open source проектів є безплатними, але "безкоштовність" не входить у визначення поняття open source. У open source проектів є можливості побічно стягувати плату завдяки подвійному ліцензуванню чи обмеженим можливостям, в той же час дотримуючись офіційного визначення open source.

## Чи слід мені запускати власний open source проект?

Коротка відповідь — так, тому що не залежно від результату, запуск власного проекту це чудовий спосіб зрозуміти як працює open source.

Якщо ви ніколи не мали open source проекта до цього, то можете нервувати з приводу того що скажуть інші, або чи взагалі хтось це помітить. Якщо звучить знайомо, ви не одні!

Open source робота це як і будь яка інша творча діяльність, як письмо чи живопис. Поділитись своєю працею з усім світом може бути лячно, але практикуватись — це єдиний спосіб стати краще, навіть якщо ви не маєте аудиторії.

Якщо ви ще не переконались, присвятіть хвильку роздумам про свої цілі. Якими вони могли б бути?

### Визначення ваших цілей

Цілі можуть допомогти вам усвідомити над чим працювати, чому сказати «ні», або де вам знадобиться стороння допомога. Почніть з запитання до себе: _чому я роблю цей проект open source?_

Не існує єдиної вірної відповіді на це питання. Ви можете мати багато цілей для одного проекту, або різні проекти з різними цілями.

Якщо вашою метою є лише показати результати своєї роботи, вам мабуть не знадобиться співпраця з іншими і ви навіть можете вказати це у файлі README. З іншого боку, якщо ви бажаєте залучити до проекту інших учасників, то варто попрацювати над документацією, щоб новачки почувались «бажаними гостями».

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/3520168?v=3&s=460" class="pquote-avatar" alt="avatar">
  Якось я створив для власних потреб UIAlertView, а потім вирішив зробити його open source. Тож я змінив його, зробив більш динамічним, та завантажив на GitHub. Також я написав деяку документацію, де пояснювалось як інші розробники можуть використати це у своїх проектах. Напевне, ніхто й ніколи цим так і не скористався, бо це був простенький проект, але я був дуже задоволений своїм внеском.
  <p markdown="1" class="pquote-credit">
— @mavris, ["Self-taught Software Developers: Why Open Source is important to us"](https://medium.com/rocknnull/self-taught-software-engineers-why-open-source-is-important-to-us-fe2a3473a576#.zhwo5krlq)
  </p>
</aside>

Разом з ростом проекту вашій спільноті може знадобитись від вас дещо більше, ніж просто код. Відповіді на питання, перевірка коду та популяризація вашого проекту також є важливими завданнями в open source проекті.

Кількість часу, що витрачається на задачі не пов’язані з написанням коду, залежатиме від розміру та сфери вашого проекту. Втім, ви маєте бути готовими взяти їх на себе або знайти когось у поміч.

**Якщо ви частина компанії, що займається open source проектом,** упевніться що ваш проект володіє внутрішніми ресурсами достатніми для процвітання. Вам знадобиться визначити хто опікуватиметься проектом після запуску та як ви розподілятимете задачі поміж учасниками спільноти.

У випадку, коли для просування та підтримки проекту необхідні спеціальний бюджет чи додатковий персонал, всі ці питання мають обговорюватись заздалегідь.

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/1857993?v=3&s=460" class="pquote-avatar" alt="avatar">
  На старті open source проекту важливо переконатись, що у ваших процесах управління враховуються внески та можливості спільноти згуртованої навколо проекту. Не бійтесь залучати учасників, що не задіяні у ключових аспектах проекту. Особливо, якщо вони роблять часті внески.
  <p markdown="1" class="pquote-credit">
— @captainsafia, ["So you wanna open source a project, eh?"](https://writing.safia.rocks/2016/12/06/so-you-wanna-open-source-a-project-eh/)
  </p>
</aside>

### Внески в інші проекти

Якщо у вас на меті стоїть навчитись співпрацювати з іншими чи зрозуміти як працює open source, розгляньте можливість вашої участі в існуючому проекті. Почніть з проекту, яким ви вже користуєтесь і любите. Допомога проекту може полягати навіть у досить простих діях — на зразок виправлення помилок у тексті чи оновлення документації.

Якщо ж ви не впевнені як приєднатись до чужого проекту і з чого почати, ознайомтесь із нашим матеріалом на цю тему — [Як зробити внесок в Open Source](../how-to-contribute/).

## Launching your own open source project

There is no perfect time to open source your work. You can open source an idea, a work in progress, or after years of being closed source.

Generally speaking, you should open source your project when you feel comfortable having others view, and give feedback on, your work.

No matter which stage you decide to open source your project, every project should include the following documentation:

* [Open source license](https://help.github.com/articles/open-source-licensing/#where-does-the-license-live-on-my-repository)
* [README](https://help.github.com/articles/create-a-repo/#commit-your-first-change)
* [Contributing guidelines](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)
* [Code of conduct](../code-of-conduct/)

As a maintainer, these components will help you communicate expectations, manage contributions, and protect everyone's legal rights (including your own). They significantly increase your chances of having a positive experience.

If your project is on GitHub, putting these files in your root directory with the recommended filenames will help GitHub recognize and automatically surface them to your readers.

### Choosing a license

An open source license guarantees that others can use, copy, modify, and contribute back to your project without repercussions. It also protects you from sticky legal situations. **You must include a license when you launch an open source project.**

Legal work is no fun. The good news is that you can copy and paste an existing license into your repository. It will only take a minute to protect your hard work.

[MIT](https://choosealicense.com/licenses/mit/), [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/), and [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) are the most popular open source licenses, but [there are other options](https://choosealicense.com) to choose from.

When you create a new project on GitHub, you are given the option to select a license. Including an open source license will make your GitHub project open source.

![pick a license](/assets/images/starting-a-project/repository-license-picker.png)

If you have other questions or concerns around the legal aspects of managing an open source project, [we've got you covered](../legal/).

### Writing a README

READMEs do more than explain how to use your project. They also explain why your project matters, and what your users can do with it.

In your README, try to answer the following questions:

* What does this project do?
* Why is this project useful?
* How do I get started?
* Where can I get more help, if I need it?

You can use your README to answer other questions, like how you handle contributions, what the goals of the project are, and information about licenses and attribution. If you don't want to accept contributions, or your project is not yet ready for production, write this information down.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/168572?v=3&s=460" class="pquote-avatar" alt="avatar">
  Better documentation means more users, less support requests, and more contributors. (...) Remember that your readers aren't you. There are people who might come to a project who have completely different experiences.
  <p markdown="1" class="pquote-credit">
— @limedaring, ["Writing So Your Words Are Read (video)"](https://www.youtube.com/watch?v=8LiV759Bje0&list=PLmV2D6sIiX3U03qc-FPXgLFGFkccCEtfv&index=10)
  </p>
</aside>

Sometimes, people avoid writing a README because they feel like the project is unfinished, or they don't want contributions. These are all very good reasons to write one.

For more inspiration, try using @18F's ["Making READMEs Readable"](https://pages.18f.gov/open-source-guide/making-readmes-readable/) or @PurpleBooth's [README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) to write a complete README.

When you include a README file in the root directory, GitHub will automatically display it on the repository homepage.

### Writing your contributing guidelines

A CONTRIBUTING file tells your audience how to participate in your project. For example, you might include information on:

* How to file a bug report (try using [issue and pull request templates](https://github.com/blog/2111-issue-and-pull-request-templates))
* How to suggest a new feature
* How to set up your environment and run tests

In addition to technical details, a CONTRIBUTING file is an opportunity to communicate your expectations for contributions, such as:

* The types of contributions you're looking for
* Your roadmap or vision for the project
* How contributors should (or should not) get in touch with you

Using a warm, friendly tone and offering specific suggestions for contributions (such as writing documentation, or making a website) can go a long way in making newcomers feel welcomed and excited to participate.

For example, [Active Admin](https://github.com/activeadmin/activeadmin/) starts [its contributing guide](https://github.com/activeadmin/activeadmin/blob/master/CONTRIBUTING.md) with:

> First off, thank you for considering contributing to Active Admin. It's people like you that make Active Admin such a great tool.

In the earliest stages of your project, your CONTRIBUTING file can be simple. You should always explain how to report bugs or file issues, and any technical requirements (like tests) to make a contribution.

Over time, you might add other frequently asked questions to your CONTRIBUTING file. Writing down this information means fewer people will ask you the same questions over and over again.

For more help with writing your CONTRIBUTING file, check out @nayafia's [contributing guide template](https://github.com/nayafia/contributing-template/blob/master/CONTRIBUTING-template.md) or @mozilla's ["How to Build a CONTRIBUTING.md"](http://mozillascience.github.io/working-open-workshop/contributing/).

Link to your CONTRIBUTING file from your README, so more people see it. If you [place the CONTRIBUTING file in your project's repository](https://help.github.com/articles/setting-guidelines-for-repository-contributors/), GitHub will automatically link to your file when a contributor creates an issue or opens a pull request.

![contributing guidelines](/assets/images/starting-a-project/Contributing-guidelines.jpg)

### Establishing a code of conduct

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/11214?v=3&s=460" class="pquote-avatar" alt="avatar">
  We’ve all had experiences where we faced what was probably abuse either as a maintainer trying to explain why something had to be a certain way, or as a user...asking a simple question. (...) A code of conduct becomes an easily referenced and linkable document that indicates that your team takes constructive discourse very seriously.
  <p markdown="1" class="pquote-credit">
— @mlynch, ["Making Open Source a Happier Place"](https://medium.com/ionic-and-the-mobile-web/making-open-source-a-happier-place-3b90d254f5f#.v4qhl7t7v)
  </p>
</aside>

Finally, a code of conduct helps set ground rules for behavior for your project's participants. This is especially valuable if you're launching an open source project for a community or company. A code of conduct empowers you to facilitate healthy, constructive community behavior, which will reduce your stress as a maintainer.

For more information, check out our [Code of Conduct guide](../code-of-conduct/).

In addition to communicating _how_ you expect participants to behave, a code of conduct also tends to describe who these expectations apply to, when they apply, and what to do if a violation occurs.

Much like open source licenses, there are also emerging standards for codes of conduct, so you don't have to write your own. The [Contributor Covenant](http://contributor-covenant.org/) is a drop-in code of conduct that is used by [over 40,000 open source projects](http://contributor-covenant.org/adopters/), including Kubernetes, Rails, and Swift. No matter which text you use, you should be prepared to enforce your code of conduct when necessary.

Paste the text directly into a CODE_OF_CONDUCT file in your repository. Keep the file in your project's root directory so it's easy to find, and link to it from your README.

## Naming and branding your project

Branding is more than a flashy logo or catchy project name. It's about how you talk about your project, and who you reach with your message.

### Choosing the right name

Pick a name that is easy to remember and, ideally, gives some idea of what the project does. For example:

* [Sentry](https://github.com/getsentry/sentry) monitors apps for crash reporting
* [Thin](https://github.com/macournoyer/thin) is a fast and simple Ruby web server

If you're building upon an existing project, using their name as a prefix can help clarify what your project does (ex. [node-fetch](https://github.com/bitinn/node-fetch) brings `window.fetch` to Node.js).

Consider clarity above all. Puns are fun, but remember that some jokes might not translate to other cultures or people with different experiences from you. Some of your potential users might be company employees: you don't want to make them uncomfortable when they have to explain your project at work!

### Avoiding name conflicts

[Check for open source projects with a similar name](http://ivantomic.com/projects/ospnc/), especially if you share the same language or ecosystem. If your name overlaps with a popular existing project, you might confuse your audience.

If you want a website, Twitter handle, or other properties to represent your project, make sure you can get the names you want. Ideally, [reserve those names now](https://instantdomainsearch.com/) for peace of mind, even if you don't intend to use them just yet.

Make sure that your project's name doesn't infringe upon any trademarks. A company might ask you to take down your project later on, or even take legal action against you. It's just not worth the risk.

You can check the [WIPO Global Brand Database](http://www.wipo.int/branddb/en/) for trademark conflicts. If you're at a company, this is one of the things your [legal team can help you with](../legal/).

Finally, do a quick Google search for your project name. Will people be able to easily find your project? Does something else appear in the search results that you wouldn't want them to see?

### How you write (and code) affects your brand, too!

Throughout the life of your project, you'll do a lot of writing: READMEs, tutorials, community documents, responding to issues, maybe even newsletters and mailing lists.

Whether it's official documentation or a casual email, your writing style is part of your project's brand. Consider how you might come across to your audience and whether that is the tone you wish to convey.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/11321?v=3&s=460" class="pquote-avatar" alt="avatar">
  I tried to be involved with every thread on the mailing list, and showing exemplary behaviour, being nice to people, taking their issues seriously and trying to be helpful overall. After a while, people stuck around not to only ask questions, but to help with the answering as well, and to my complete delight, they mimicked my style.
  <p markdown="1" class="pquote-credit">
— @janl on [CouchDB](https://github.com/apache/couchdb), ["Sustainable Open Source"](http://writing.jan.io/2015/11/20/sustainable-open-source.html)
  </p>
</aside>

Using warm, inclusive language (such as "them", even when referring to the single person) can go a long way in making your project feel welcoming to new contributors. Stick to simple language, as many of your readers may not be native English speakers.

Beyond how you write words, your coding style may also become part of your project's brand. [Angular](https://github.com/johnpapa/angular-styleguide) and [jQuery](http://contribute.jquery.org/style-guide/js/) are two examples of projects with rigorous coding styles and guidelines.

It isn't necessary to write a style guide for your project when you're just starting out, and you may find that you enjoy incorporating different coding styles into your project anyway. But you should anticipate how your writing and coding style might attract or discourage different types of people. The earliest stages of your project are your opportunity to set the precedent you wish to see.

## Your pre-launch checklist

Ready to open source your project? Here's a checklist to help. Check all the boxes? You're ready to go! [Click "publish"](https://help.github.com/articles/making-a-private-repository-public/) and pat yourself on the back.

**Documentation**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox1" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox1" class="overflow-hidden d-block text-normal">
    Project has a LICENSE file with an open source license
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox2" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox2" class="overflow-hidden d-block text-normal">
    Project has basic documentation (README, CONTRIBUTING, CODE_OF_CONDUCT)
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox3" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox3" class="overflow-hidden d-block text-normal">
    The name is easy to remember, gives some idea of what the project does, and does not conflict with an existing project or infringe on trademarks
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox4" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox4" class="overflow-hidden d-block text-normal">
    The issue queue is up-to-date, with issues clearly organized and labeled
  </label>
</div>

**Code**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox5" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox5" class="overflow-hidden d-block text-normal">
    Project uses consistent code conventions and clear function/method/variable names
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox6" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox6" class="overflow-hidden d-block text-normal">
    The code is clearly commented, documenting intentions and edge cases
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox7" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox7" class="overflow-hidden d-block text-normal">
    There are no sensitive materials in the revision history, issues, or pull requests (ex. passwords or other non-public information)
  </label>
</div>

**People**

If you're an individual:

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox8" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox8" class="overflow-hidden d-block text-normal">
  You've talked to the legal department and/or understand the IP and open source policies of your company (if you're an employee somewhere)
  </label>
</div>

If you're a company or organization:

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox9" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox9" class="overflow-hidden d-block text-normal">
    You've talked to your legal department
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox10" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox10" class="overflow-hidden d-block text-normal">
    You have a marketing plan for announcing and promoting the project
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox11" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox11" class="overflow-hidden d-block text-normal">
    Someone is committed to managing community interactions (responding to issues, reviewing and merging pull requests)
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox12" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox12" class="overflow-hidden d-block text-normal">
    At least two people have administrative access to the project
  </label>
</div>

## You did it!

Congratulations on open sourcing your first project. No matter the outcome, working in public is a gift to the community. With every commit, comment, and pull request, you're creating opportunities for yourself and for others to learn and grow.

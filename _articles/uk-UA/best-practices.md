---
locale: uk-UA
title: Найкращі практики для супровідників.
description: 'Зробіть своє життя, як супровідника open source проекту, простішим: від документування процесів до використання спільноти.'
class: best-practices
toc:
  Що-означає-бути-супровідником: "Що означає бути супровідником?"
  Задокументуйте-свої-процеси: "Задокументуйте свої процеси"
  Навчіться-казати-ні: "Навчіться казати «ні»"
  Використовуйте-свою-спільноту: "Використовуйте свою спільноту"
  bring-in-the-robots: "Bring in the robots"
  its-okay-to-hit-pause: "It’s okay to hit pause"
order: 5
image: /assets/images/cards/best-practices.png
---

## Що означає бути супровідником?

Якщо ви супроводжуєте open source проект, який використовує чимало людей, ви помітите, що починаєте менше писати код і більше відповідати на іш'ю.

На ранніх етапах проекту ви експериментуєте з новими ідеями та прймаєте рішення, виходячи зі своїх бажань. Як тільки популярність проекту зросте, ви більше співпрацюватимете зі своїми користувачами та учасниками.

Супровід проекту вимагає чогось більшого, ніж написання коду. Ці задачі часто непередбачувані, втім вони не менш важливі для проекту, що розвивається. Ми зібрали декілька способів, які полегшать ваше життя: від документування процесів до використання своєї спільноти.

## Задокументуйте свої процеси

Записувати різні речі — це одна з найважливіших речей, що ви, як супровідник, можете зробити.

Документування не лише допоможе вам краще сформулювати думки, а також допоможе іншим людям зрозуміти, що їм потрібно або чого очікувати, ще до того, як вони спитають.

Записування спростить відмову, якщо щось не входить у ваші рамки. Також це допоможе іншим зробити перший крок і приєднатися до співпраці. Ви ніколи не знаєте, хто читає чи використовує ваш проект.

Якщо ви не пишете розгорнуті абзаци, занотовувати основні моменти все одно краще, ніж не писати узагалі нічого.

### Запишіть своє бачення проекту

Для початку запишіть мету свого проекту. Додайте її до файлу README або створіть окремий файл із назвою VISION (БАЧЕННЯ). Якщо є й інші матеріали, які можуть допомогти (наприклад, дорожня карта проекту), зробіть їх також публічними.

Наявність чіткого, задокументованого бачення дозволить вам залишатися сфокусованим та уникнути так званого "посунення рамок" внаслідок внесків (contributions) інших людей.

Наприклад, @lord зрозумів, що наявність бачення проекту допомагає йому визначатися, на які запити витрачати час. Він, як новий супровідник, шкодує, що не притримувався рамок проекту, коли отримав перший запит щодо [Slate](htts://github.com/lord/slate).

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/1976330?v=3&s=460" class="pquote-avatar" alt="avatar" alt="@lord avatar">
  Я зробив дуже незграбно. Я не доклав зусиль щоб знайти повне рішення. Замість часткового рішення я волів би сказати "У мене зараз немає на це часу, але я додам це до списку бажаних у довготривалій перспективі речей".
  <p markdown="1" class="pquote-credit">
— @lord, ["Поради для нових супровідників open source"](https://lord.io/blog/2014/oss-tips/)
  </p>
</aside>

### Повідомляйте про свої очікування

Написання правил часто дратує. Інколи ви навіть можете почуватися наче контролюєте поведінку інших людей або псуєте їм усі веселощі.

Втім, записані та чесно застосовувані, хороші правила посилюють супровідників. Вони не дають вам бути затягнутим у ті речі, які ви не бажаєте робити.

Більшість із тих людей, які знаходять ваш проект, нічого не знають ані про вас, ані про ваші обставини. Вони можуть вважати, що ви отримуєте платню за роботу над проектом, особливо якщо самі цим частенько послуговуються і залежать від цього. Можливо, ви колись приділяли багато часу своєму проекту, але зараз сильно зайняті на новій роботі або з новим членом своєї сім'ї.

Це цілком нормально! Лишень переконайтеся, що інші люди знають про це.

Якщо супровід проекту відбувається частково або повністю на волонтерських засадах, будьте чесними щодо того, скільки часу ви маєте. Це не те саме, що і час, який, на вашу думку, цей проект потребує, або час, який ви хотіли б на нього витрачати.

Ось декільки правил, які варто написати:

* Як розглядаються та приймаються внески (_Чи потрібні тести? Шаблон для створення іш'ю?_)
* Види внесків, які ви приймете (_Можливо, ви бажаєте допомоги лише з конкретним фрагментом вашого коду?_)
* Коли доречно повторювати запит (_напр. "Очікуйте відповідь від супровідника протягом 7 днів. Якщо до того часу ви нічого не почуєте, не соромтеся нагадати про себе в обговоренні."_)
* Скільки часу ви приділяєте проекту (_напр. "Цьому проекту ми приділяємо приблизно 5 годин на тиждень"_)

[Jekyll](https://github.com/jekyll/jekyll/tree/master/docs), [CocoaPods](https://github.com/CocoaPods/CocoaPods/wiki/Communication-&-Design-Rules), та [Homebrew](https://github.com/Homebrew/brew/blob/bbed7246bc5c5b7acb8c1d427d10b43e090dfd39/docs/Maintainers-Avoiding-Burnout.md), — ось декілька прикладів проектів, що мають основоположні правила для супровідників та учасників.

### Комунікуйте публічно

Не забудьте записувати і взаємодії також. Усюди, де це можна, тримайте комунікації щодо проекту публічними. Хтось намагається написати вам особисто для обговорення функціональності або необхідної допомоги — ввічливо направте їх у публічний канал обговорень, такий як поштова розсилка або реєстр іш'ю (issue tracker).

Якщо ви особисто зустрічаєтеся з іншими супровідниками або приймаєте важливі рішення, задокументуйте ці обговорення публічно, навіть якщо це лише публікування ваших нотаток.

Таким чином, будь-хто, хто долучиться до вашої спільноти, володітиме тією ж інформацією, що й людина, яка брала участь у проекті впродовж років.

## Навчіться казати «ні»

Отже, ви все записали. В ідеальному світі усі прочитають вашу документацію, але в реальному вам доведеться нагадувати іншим про існування цих знань.

Утім, наявність інформації у письмовому вигляді дає можливість знеособити ситуації, коли вам необхідно забезпечити дотримання правил.

Непросто казати «ні». Але відповідь _"Ваш внесок не відповідає критеріям проекту"_ є менш особистою, ніж _"Мені не до вподоби ваш внесок"_.

Вам доведеться казати «ні» у багатьох ситуаціях, з якими ви, як супровідник, будете мати справу. Наприклад, запити функціоналу, які виходять за рамки проекту; люди, котрі зводять обговорення нанівець; виконання непотрібної роботи для інших.

### Підртимуйте дружній тон спілкування

В основному вам доведеться відмовляти у відкритих іш'ю і чисельних пул-реквестах. Як супровідник, ви неминуче отримаєте такі пропозиції щодо проекту, які не захочете приймати.

Можливо, внесок змінює рамки проекту або не співпадає з вашим баченням. Можливо, хоч ідея і чудова, її реалізація залишає бажати кращого.

Незалежно від причин, завжди можна тактовно поводитися по відношенню до внесків, які не відповідають стандартам вашого проекту.

Припустимо, ви отримали внесок, який не бажаєте приймати. Першою реакцією може виникнути бажання проігнорувати його або зробити вигляд, ніби ви його не бачили. Учинивши так, ви можете зачепити почуття іншої людини або ж навіть демотивувати інших потенційних учасників своєї спільноти.

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/869950?v=3&s=400" class="pquote-avatar" alt="avatar" alt="@KrauseFx avatar">
  Ключем до підтримки великих open source проектів є рух іш'ю. Намагайтеся уникати їх застою. Якщо ви iOS розробник, то знаєте наскільки може розчаровувати відкриття «радарів». Отримати відповідь ви можете аж через 2 роки, при цьому вона може містити пропозицію спробувати ще раз, але вже з останньою версією iOS.
  <p markdown="1" class="pquote-credit">
— @KrauseFx, ["Розширення open source спільнот"](https://krausefx.com/blog/scaling-open-source-communities)
  </p>
</aside>

Не залишайте небажані внески відкритими тільки тому, що почуваєтеся винним або хочете бути ввічливим. З часом через іш'ю та пул-реквести, що залишилися без відповіді, робота над вашим проектом стане більш стресовою та лячною.

Набагато краще одразу закривати внески, які ви точно не бажаєте приймати. Якщо ваш проект вже перевантажений надмірно великим списком завдань, то у @steveklabnik є пропозиція щодо того, [як ефективно впорядкувати іш'ю](http://words.steveklabnik.com/how-to-be-an-open-source-gardener).

До того ж, ігнорування внесків посилає негативний сигнал для спільноти. Робити внесок до проекту — лячно, особливо, якщо хтось це робить вперше. Навіть якщо ви не приймаєте внесок, подякуйте авторові за нього та за проявлений інтерес. Для вас це не складно, а авторові буде приємно.

Якщо ви не бажаєте приймати внесок:

* **Подякуйте авторам** за внесок.
* **Поясніть, чому саме цей внесок не підходить** проекту та, якщо можете, запропонуйте чіткі пропозиції для покращення. Будьте люб'язні, але і непохитні.
* **Додайте посилання на відповідну документацію**, якщо маєте його. Якщо ви помічаєте, що запити, які ви не бажаєте приймати, повторюються, — задокументуйте інформацію про це, аби не відповідати одне й те саме.
* **Закрийте запит**.

Зазвичай, для відповіді вам має бути достатньо 1-2 речень. Наприклад, коли користувач [celery](https://github.com/celery/celery) повідомив про помилку, пов'язану із Windows, @berkerpeksag [відповів](https://github.com/celery/celery/issues/3383):

![celery screenshot](/assets/images/uk-UA/best-practices/celery.png)

Якщо сама лише думка про відмову лякає вас, знайте: ви не одні. Як [зазначив](https://blog.jessfraz.com/post/the-art-of-closing/) @jessfraz:

> Я говорив із супровідниками різних open source проектів, таких як Mesos, Kubernetes, Chromium. І вони всі погодилися, що однією з найважчих речей, які їм, як супровідникам, доводиться робити, — це казати «ні» латкам (patch), яких вони не бажають.

Не варто почуватися винним через небажання приймати чийсь внесок. Першим правилом open source є ([згідно з](https://twitter.com/solomonstre/status/715277134978113536) @shykes): _"«Ні» — це тимчасово, «так» — це назавжди"_. Перейматися через ентузіазм іншої людини — добре, але варто пам'ятати, що відхилення внеску — це не відхилення людини, що стоїть за ним.

Врешті-решт, якщо внесок залишає бажати кращого, ви не зобов'язані приймати його. Будьте люб'язними та чуйними, коли люди роблять внески у ваш проект, але приймайте лише ті зміни, які, на вашу думку, зроблять ваш проект кращим. Чим частіше ви практикуєтеся казати «ні», тим легше стає це робити. Повірте.

### Грайте на випередження

Для того, щоб зменшити обсяг небажаних внесків, поясніть у керівництві про співпрацю процеси створення та прийняття внесків до вашого проекту.

Якщо ви отримуєте дуже багато низькоякісних внесків, вимагайте, щоб учасники попередньо виконали певні дії, наприклад:

* Заповнили шаблон/контрольний список для іш'ю або пул-реквесту
* Відкрили іш'ю перед тим, як робити пул-реквест

Якщо вони не слідують вашим правилам — одразу закривайте іш'ю та вказуйте на документацію.

Хоч такий підхід спершу і може видатися недобрим, гра на випередження, насправді, вигідна обом сторонам. Вона зменшує шанс того, що хтось витратить чимало часу на пул-реквест, який ви не збираєтеся приймати. Також це полегшує управління робочим навантаженням.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/125011" class="pquote-avatar" alt="avatar">
  В ідеалі, поясніть і опишіть у файлі CONTRIBUTING.md, як ще до початку роботи отримати краще розуміння, чи буде ця робота прийнята, чи ні.
  <p markdown="1" class="pquote-credit">
— @mikemcquaid, ["Закриваємо пул-реквести люб'язно"](https://github.com/blog/2124-kindly-closing-pull-requests)
  </p>
</aside>

Іноді, коли ви відмовляєте, ваш потенційний учасник може засмутитися або почати критикувати ваше рішення. У випадку, якщо поведінка цього учасника стає ворожою (недружньою), [вжийте заходів, щоб розрядити обстановку](https://github.com/jonschlinkert/maintainers-guide-to-staying-positive#action-items), або ж навіть виключіть його зі спільноти, якщо він не бажає конструктивно співпрацювати.

### Використовуйте наставництво

Можливо, дехто у вашій спільноті регулярно надсилає внески, які не підходять під стандарти вашого проекту. Для обох сторін неодноразово проходити етап відмови може бути неприємно.

Якщо ви бачите, що хтось сповнений ентузіазму щодо вашого проекту, але при цьому, на вашу думку, потребує поліпшення, будьте терплячі. У кожній ситуації чітко поясніть, чому внесок не співпадає з очікуваннями проекту. Намагайтеся вказати на завдання, яке простіше або менш неоднозначне. Наприклад, іш'ю позначене як _"хороша перша вада"_, для того, щоб почати. Якщо ви маєте на це час, то подумайте над тим, щоб наставляти учасника протягом його роботи над першим внеском. Або ж знайдіть у спільноті когось іншого, хто був би не проти цим зайнятися.

## Використовуйте свою спільноту

Вам необов'язково все робити власноруч. Спільнота вашого проекту існує не просто так! Навіть якщо ви ще не маєте активних учасників у спільноті, якщо ви маєте багато користувачів — дайте їм якусь роботу.

### Розподіляйте навантаження

Для пошуку людей, які могли б активно займатися проектом, почніть з розпитувань.

Якщо ви бачите, що нові учасники час від часу роблять внески, визнайте їхню роботу, запрпонувавши їм більше відповідальності. Якщо інші учасники бажають досягти лідерських позицій у проекті, задокументуйте, як вони можуть це зробити.

Заохочуйте інших [розділити права власності на проект](../building-community/#share-ownership-of-your-project) — це помітно зменшить навантаження на вас, — з'ясувала @lmccart під час роботи над своїм проектом [p5.js](https://github.com/processing/p5.js?files=1).

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/191056?v=3&s=460" class="pquote-avatar" alt="avatar">
  Я казала: "Так, будь хто може взяти участь і для цього не потрібно мати багато досвіду у програмуванні [...]." Люди реєструвалися, щоб прийти [на захід], і тоді мені стало цікаво: чи дійсно все так, як я кажу? Мали прийти майже 40 людей, і навряд я змогла би сидіти з кожним із них... Але люди прийшли разом, і все спрацювало. Як тільки комусь із них вдавалося розібратися, то та людина вже могла навчити і свого сусіда.
  <p markdown="1" class="pquote-credit">
—  @lmccart, ["Що “Open Source” взагалі означає? Видання p5.js"](https://medium.com/@kenjagan/what-does-open-source-even-mean-p5-js-edition-98c02d354b39#.chnjlag7p)
  </p>
</aside>

Якщо вам треба відійти від проекту, ненадовго чи назавжди, — немає нічого ганебного в тому, щоб попросити когось приглянути за ним замість вас.

Якщо інші люди зацікавлені у тому, як розвивається ваш проект, — дайте їм доступ, можливість комітити, або формально передайте управління комусь іншому. Якщо хтось зробив форк вашого проекту та активно супроводжує його деінде, подумайте над тим, щоб додати посилання з вашого проекту на форк. Це ж так круто, що так багато людей хочуть, аби ваш проект продовжував жити!

@progrium [виявив](http://progrium.com/blog/2015/12/04/leadership-guilt-and-pull-requests/), що документування бачення його проекту [Dokku](https://github.com/dokku/dokku) допомогло поставленим цілям жити навіть після того, як він перестав займатися проектом:
@progrium [found that](http://progrium.com/blog/2015/12/04/leadership-guilt-and-pull-requests/) documenting the vision for his project, [Dokku](https://github.com/dokku/dokku), helped those goals live on even after he stepped away from the project:

> Я написав вікі-сторінку, яка описувала, чого я бажаю та чому. Для мене стало несподіванкою те, що супровідники почали розвивати проект у тому самому напрямку. Чи робили вони все так, як би це робив я? Не завжди. Але все ж це зробило проект ближчим до того, що я написав.

### Дайте іншим будувати ті рішення, яких вони потребують

Якщо потенційний учасник має відмінну від вашої точку зору щодо того, що повинен робити проект, ви можете ввічливо заохотити його розвивати цю ідею у його власному форку.

Форк проекту не означає щось погане. Можливість копіювати та змінювати проекти — одна з найкращих штук в open source. Надихайте учасників спільноти працювати над їхніми форками — це надасть їм віддушину для творчості, яка не конфліктуватиме з вашим баченням проекту.

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/481677?v=3&s=400" class="pquote-avatar" alt="avatar">
  Я намагаюся догодити 80% сценаріїв використання. Якщо ви один із рідкісних однорогів — будь ласка, зробіть форк. Я не ображуся! Мої публічні проекти майже завжди мають на меті вирішити найбільш поширені проблеми; я намагаюся спростити для інших процес заглиблення за допомогою або створення форку, або розширення моєї роботи.

  <p markdown="1" class="pquote-credit">
— @geerlingguy, ["Чому я закриваю пул-реквести"](https://www.jeffgeerling.com/blog/2016/why-i-close-prs-oss-project-maintainer-notes)
  </p>
</aside>

Те ж саме стосується користувачів, які бажають ті рішення, що ви просто не здатні побудувати. Пропонуючи API та налаштовувані хуки, ви можете допомогти іншим вирішити їхні потреби, не змінюючи безпосередньо вихідний код. @orta [виявив](http://artsy.github.io/blog/2016/07/03/handling-big-projects/), що заохочення до створення плагінів для CocoaPods призело до "деяких із найцікавіших ідей":

> Коли проект стає справді великим, майже неминуче те, що супровідники стають куди більш консервативними щодо додоавання нового коду. Ви починаєте дуже добре казати "ні", але багато людей мають виправдані потреби. Тож натомість ви перетворюєте свій інструмент на платформу.

## Bring in the robots

Just as there are tasks that other people can help you with, there are also tasks that no human should ever have to do. Robots are your friend. Use them to make your life as a maintainer easier.

### Require tests and other checks to improve the quality of your code

One of the most important ways you can automate your project is by adding tests.

Tests help contributors feel confident that they won't break anything. They also make it easier for you to review and accept contributions quickly. The more responsive you are, the more engaged your community can be.

Set up automatic tests that will run on all incoming contributions, and ensure that your tests can easily be run locally by contributors. Require that all code contributions pass your tests before they can be submitted. You'll help set a minimum standard of quality for all submissions.

If you add tests, make sure to explain how they work in your CONTRIBUTING file.

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/812892?v=3&s=460" class="pquote-avatar" alt="avatar">
  I believe that tests are necessary for all code that people work on. If the code was fully and perfectly correct, it wouldn't need changes – we only write code when something is wrong, whether that's "It crashes" or "It lacks such-and-such a feature". And regardless of the changes you're making, tests are essential for catching any regressions you might accidentally introduce.
  <p markdown="1" class="pquote-credit">
— @edunham, ["Rust's Community Automation"](http://edunham.net/2016/09/27/rust_s_community_automation.html)
  </p>
</aside>

### Use tools to automate basic maintenance tasks

The good news about maintaining a popular project is that other maintainers have probably faced similar issues and built a solution for it.

There are a [variety of tools available](https://github.com/integrations) to help automate some aspects of maintenance work. A few examples:

* [semantic-release](https://github.com/semantic-release/semantic-release) automates your releases
* [mention-bot](https://github.com/facebook/mention-bot) mentions potential reviewers for pull requests
* [Danger](https://github.com/danger/danger) helps automate code review

For bug reports and other common contributions, GitHub has [Issue Templates and Pull Request Templates](https://github.com/blog/2111-issue-and-pull-request-templates), which you can create to streamline the communication you receive. You can also set up [email filters](https://github.com/blog/2203-email-updates-about-your-own-activity) to manage your email notifications.

If you want to get a little more advanced, style guides and linters can standardize project contributions and make them easier to review and accept.

However, if your standards are too complicated, they can increase the barriers to contribution. Make sure you're only adding enough rules to make everyone's lives easier.

If you're not sure which tools to use, look at what other popular projects do, especially those in your ecosystem. For example, what does the contribution process look like for other Node modules? Using similar tools and approaches will also make your process more familiar to your target contributors.

## It's okay to hit pause

Open source work once brought you joy. Maybe now it's starting to make you feel avoidant or guilty.

Perhaps you're feeling overwhelmed or a growing sense of dread when you think about your projects. And meanwhile, the issues and pull requests pile up.

Burnout is a real and pervasive issue in open source work, especially among maintainers. As a maintainer, your happiness is a non-negotiable requirement for the survival of any open source project.

Although it should go without saying, take a break! You shouldn't have to wait until you feel burned out to take a vacation. @brettcannon, a Python core developer, decided to take [a month-long vacation](http://www.snarky.ca/why-i-took-october-off-from-oss-volunteering) after 14 years of volunteer OSS work.

Just like any other type of work, taking regular breaks will keep you refreshed, happy, and excited about your work.

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/36432?v=3&s=400" class="pquote-avatar" alt="avatar">
  In maintaining WP-CLI, I've discovered I need to make myself happy first, and set clear boundaries on my involvement. The best balance I've found is 2-5 hours per week, as a part of my normal work schedule. This keeps my involvement a passion, and from feeling too much like work. Because I prioritize the issues I'm working on, I can make regular progress on what I think is most important.
  <p markdown="1" class="pquote-credit">
— @danielbachhuber, ["My condolences, you're now the maintainer of a popular open source project"](https://runcommand.io/2016/06/26/my-condolences-youre-now-the-maintainer-of-a-popular-open-source-project/)
  </p>
</aside>

Sometimes, it can be hard to take a break from open source work when it feels like everybody needs you. People may even try to make you feel guilty for stepping away.

Do your best to find support for your users and community while you're away from a project. If you can't find the support you need, take a break anyway. Be sure to communicate when you're not available, so people aren't confused by your lack of responsiveness.

Taking breaks applies to more than just vacations, too. If you don't want to do open source work on weekends, or during work hours, communicate those expectations to others, so they know not to bother you.

## Take care of yourself first!

Maintaining a popular project requires different skills than the earlier stages of growth, but it's no less rewarding. As a maintainer, you'll practice leadership and personal skills on a level that few people get to experience. While it's not always easy to manage, setting clear boundaries and only taking on what you're comfortable with will help you stay happy, refreshed, and productive.

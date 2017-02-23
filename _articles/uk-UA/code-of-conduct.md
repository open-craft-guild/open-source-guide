---
locale: en-US
title: Ваш кодекс честі
description: Забезпечте здорову й конструктивну поведінку в спільноті, адаптувавши й заохотивши дотримання кодексу честі.
class: coc
toc:
  Навіщо-мені-кодекс-честі: "Навіщо мені кодекс честі?"
  Затвердження-кодексу-честі: "Затвердження кодексу честі"
  Вирішуємо-як-вам-забезпечити-дотримання-кодексу-честі: "Вирішуємо як вам забезпечити дотримання кодексу честі"
  Приводимо-в-дію-свій-кодекс-честі: "Приводимо в дію свій кодекс честі"
order: 8
image: /assets/images/cards/coc.png
---

## Навіщо вам кодекс честі?

A code of conduct is a document that establishes expectations for behavior for your project's participants. Adopting, and enforcing, a code of conduct can help create a positive social atmosphere for your community.

Codes of conduct help protect not just your participants, but yourself. If you maintain a project, you may find that unproductive attitudes from other participants can make you feel drained or unhappy about your work over time.

A code of conduct empowers you to facilitate healthy, constructive community behavior. Being proactive reduces the likelihood that you, or others, will become fatigued with your project, and helps you take action when someone does something you don't agree with.

## Затвердження кодексу честі

Try to establish a code of conduct as early as possible: ideally, when you first create your project.

In addition to communicating your expectations, a code of conduct describes the following:

* Where the code of conduct takes effect _(only on issues and pull requests, or community activities like events?)_
* Whom the code of conduct applies to _(community members and maintainers, but what about sponsors?)_
* What happens if someone violates the code of conduct
* How someone can report violations

Wherever you can, use prior art. The [Contributor Covenant](http://contributor-covenant.org/) is a drop-in code of conduct that is used by over 40,000 open source projects, including Kubernetes, Rails, and Swift.

The [Django Code of Conduct](https://www.djangoproject.com/conduct/) and the [Citizen Code of Conduct](http://citizencodeofconduct.org/) are also two good code of conduct examples.

Place a CODE_OF_CONDUCT file in your project's root directory, and link to it from your README, so it's visible to your community.

## Вирішуємо як вам забезпечити дотримання кодексу честі

<aside markdown="1" class="pquote">
  A code of conduct that isn't (or can't be) enforced is worse than no code of conduct at all: it sends the message that the values in the code of conduct aren't actually important or respected in your community.
  <p markdown="1" class="pquote-credit">
— [Ada Initiative](https://adainitiative.org/2014/02/18/howto-design-a-code-of-conduct-for-your-community/)
  </p>
</aside>

You should explain how your code of conduct will be enforced **_before_** a violation occurs. There are several reasons to do so:

* It demonstrates that you are serious about taking action when it's needed.

* Your community will feel more reassured that complaints actually get reviewed.

* You'll reassure your community that the review process is fair and transparent, should they ever find themselves investigated for a violation.

You should give people a private way (such as an email address) to report a code of conduct violation and explain who receives that report. It could be a maintainer, a group of maintainers, or a code of conduct working group.

Don't forget that someone might want to report a violation about a person who receives those reports. In this case, give them an option to report violations to someone else. For example, @ctb and @mr-c [explain on their project](https://github.com/dib-lab/khmer/blob/master/CODE_OF_CONDUCT.rst), [khmer](https://github.com/dib-lab/khmer):

> Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by emailing **khmer-project@idyll.org** which only goes to C. Titus Brown and Michael R. Crusoe. To report an issue involving either of them please email **Judi Brown Clarke, Ph.D.** the Diversity Director at the BEACON Center for the Study of Evolution in Action, an NSF Center for Science and Technology.*

For inspiration, check out Django's [enforcement manual](https://www.djangoproject.com/conduct/enforcement-manual/) (though you may not need something this comprehensive, depending on the size of your project).

## Приводимо в дію свій кодекс честі

Sometimes, despite your best efforts, somebody will do something that violates this code. There are several ways to address negative or harmful behavior when it comes up.

### Зберіть інформацію про ситуацію

Treat each community member's voice as important as your own. If you receive a report that someone violated the code of conduct, take it seriously and investigate the matter, even if it does not match your own experience with that person. Doing so signals to your community that you value their perspective and trust their judgment.

The community member in question may be a repeat offender who consistently makes others feel uncomfortable, or they may have only said or done something once. Both can be grounds for taking action, depending on context.

Before you respond, give yourself time to understand what happened. Read through the person's past comments and conversations to better understand who they are and why they might have acted in such a way. Try to gather perspectives other than your own about this person and their behavior.

<aside markdown="1" class="pquote">
  Don’t get pulled into an argument. Don’t get sidetracked into dealing with someone else’s behavior before you’ve finished dealing with the matter at hand. Focus on what you need.
  <p markdown="1" class="pquote-credit">
— Stephanie Zvan, ["So You've Got Yourself a Policy. Now What?"](https://the-orbit.net/almostdiamonds/2014/04/10/so-youve-got-yourself-a-policy-now-what/)
  </p>
</aside>

### Зробіть те, що необхідно

After gathering and processing sufficient information, you'll need to decide what to do. As you consider your next steps, remember that your goal as a moderator is to foster a safe, respectful, and collaborative environment. Consider not only how to deal with the situation in question, but how your response will affect the rest of your community's behavior and expectations moving forward.

When somebody reports a code of conduct violation, it is your, not their, job to handle it. Sometimes, the reporter is disclosing information at great risk to their career, reputation, or physical safety. Forcing them to confront their harasser could put the reporter in a compromising position. You should handle direct communication with the person in question, unless the reporter explicitly requests otherwise.

There are a few ways you might respond to a code of conduct violation:

* **Give the person in question a public warning** and explain how their behavior negatively impacted others, preferably in the channel where it occurred. Where possible, public communication conveys to the rest of the community that you take the code of conduct seriously. Be kind, but firm in your communication.

* **Privately reach out to the person** in question to explain how their behavior negatively impacted others. You may want to use a private communication channel if the situation involves sensitive personal information. If you communicate with someone privately, it's a good idea to CC those who first reported the situation, so they know you took action. Ask the reporting person for consent before CCing them.

Sometimes, a resolution cannot be reached. The person in question may become aggressive or hostile when confronted or does not change their behavior. In this situation, you may want to consider taking stronger action. For example:

* **Suspend the person** in question from the project, enforced through a temporary ban on participating in any aspect of the project

* **Permanently ban** the person from the project

Banning members should not be taken lightly and represents a permanent and irreconcilable difference of perspectives. You should only take these measures when it is clear that a resolution cannot be reached.

## Заохочуйте поведінку, яку вам би хотілося бачити в світі 🌎

When a project seems hostile or unwelcoming, even if it's just one person whose behavior is tolerated by others, you risk losing many more contributors, some of whom you may never even meet. It's not always easy to adopt or enforce a code of conduct, but fostering a welcoming environment will help your community grow.

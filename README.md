[English](README.md) | [简体中文](README.zh-CN.md)

<a id="world-chronicle--being-read-and-keeping-your-own-explanation--被系统理解也保留自己的解释"></a>
<a id="world-chronicle--being-read-and-keeping-your-own-explanation"></a>
<a id="被系统理解也保留自己的解释"></a>

# Readable/Unreadable — being read, and keeping your own explanation

[Project page](https://ruixiaozhang.com/index_EN#work-aidirector)

Readable/Unreadable is my master's thesis work: an interactive narrative set in a fictional hospital, where a system tries to read the player, and the player can inspect, correct or refuse that reading. It is also the first game for World Chronicle, a narrative game system that I am developing. Until 9 November 2026, this overview used the name World Chronicle for the thesis.

![A ward in the Readable/Unreadable hospital prototype](docs/media/ward.webp)

A UE runtime still of the ward where a shift happens. It shows the setting, not evidence that complete tasks are playable.

<a id="how-it-plays--怎样玩"></a>
<a id="how-it-plays"></a>
<a id="怎样玩"></a>

## How it plays

Players begin by describing how they want to play and responding to a set of situated questions. The work is designed around a provisional system reading that they can inspect, expand, correct or refuse.

Inside the hospital, the player takes one of three roles (doctor, nurse or cleaner) and works a shift with a supervisor and colleagues played by AI. Both sides make their own judgements as situations unfold. Every choice is written into a world chronicle: the path that happened lights up, and the paths not taken stay visible for review afterwards.

<a id="where-it-stands-november-2026--当前进展2026-年-11-月"></a>
<a id="where-it-stands-november-2026"></a>
<a id="当前进展2026-年-11-月"></a>

## Where it stands: November 2026

In November, the doctor line runs continuously through its first half in automated play. AI colleagues walk where the story needs them, take the lift between floors, sit at a bedside, take a file from a cabinet and put it back, and step aside for others; their lines are generated live and voiced. The player's choices change what follows, and in-game review cards let the player accept, correct or black out what the system recorded. These runs use a synthetic answer set and automated input; they are not human play.

![Identity cards above colleagues](docs/media/ru-ui-office-en.webp)

An in-game view from an offline development run: Dr Zhou and Lin Chuan in the handover office. Each card shows the name, the role and ‘No confirmed purpose yet’; the current task is at the top right. Synthetic answers, not human play.

![A talk prompt in the ward](docs/media/ru-ui-ward-talk-en.webp)

An in-game view from an offline development run: the patient Liu Lan in her own ward, with the talk prompt that appears when the crosshair is on her. Synthetic answers, not human play.

The second half of the doctor line and its endings, the closing world chronicle and review, the nurse and cleaner lines, and a roughly twenty-minute play session with replay interviews are still being built and prepared; human playtests have not begun. The full questionnaire, profile fields, story branches, director rules and test material remain private.

<a id="where-it-stands-mid-term-review-october-2026--当前进展2026-年-10-月中期汇报"></a>
<a id="where-it-stands-mid-term-review-october-2026"></a>
<a id="当前进展2026-年-10-月中期汇报"></a>

## Mid-term review: October 2026

The prototype runs from the intake to an Unreal Engine hospital assembled for that session and a first-person entry. AI colleagues walk to a bedside, sit down, read a handover card and reply, and the opening story beats complete in one continuous run.

[Watch the mid-term demo (1:21, 720p, no audio)](docs/media/world-chronicle-demo-720p.mp4)

The demo uses a synthetic answer set and automated input; it is not a recording of a human player. Its opening shows sample answers to three of the spatial questions. A development panel was blurred for about fifteen seconds because it showed internal questionnaire references.

At the mid-term review, still to come: a complete shift, branches that lead choices to genuinely different consequences, and a roughly twenty-minute play session with replay interviews. Participant studies have not begun.

<a id="space-and-choice--空间与选择"></a>
<a id="space-and-choice"></a>
<a id="空间与选择"></a>

## Space and choice

![Distance at the bedside](docs/media/bedside.webp)

Beds, curtains and the space beside them decide where people stand to talk, and quietly shape what the player decides.

![How the rooms connect](docs/media/floorplan-en.webp)

One session's hospital floor. How wards, the workstation and corridors connect sets the task route and what the player passes on the way. Room names were relabelled for this page.

<a id="my-work--我的工作"></a>
<a id="my-work"></a>
<a id="我的工作"></a>

## My work

Artistic concept, interaction design, the research framework and prototype development. The thesis studies, through design, how people and AI come to understand each other, and how players explain their own choices in action and on review.

<a id="related--相关页面"></a>
<a id="related"></a>
<a id="相关页面"></a>

## Related

[AINPC CHI](https://github.com/Shawn200212/AINPC-CHI) · [AIWG](https://github.com/Shawn200212/AI-World-Generator)

[Disclosure](DISCLOSURE.md) · [Media inventory](docs/public-media.json) · [Rights and credits](RIGHTS_AND_CREDITS.md)

Overview updated 9 November 2026. The text, images and demo mirror the project website. This repository is a research overview, not a runnable project or a complete research artifact.

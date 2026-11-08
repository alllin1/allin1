# Your business. One desk. A team that does the work.

Allin1 is where the business actually runs. One account. Agents who already have jobs. Chat, mail, the tools you connect, and a folder on your own computer. You stay in charge of anything that changes.

**[Open allin1app.com and create the account](https://allin1app.com)**

<p align="center">
  <img src="https://allin1app.com/og-image.jpg?v=20260924" alt="Allin1. Your business, with its own intelligence." width="720">
</p>

## This is the workforce, not another chatbot

You talk to the business the way you would talk to a chief of staff. Atlas takes the job, hands the parts to the people who own them, and the answer comes back in the same chat.

- **One place for the team.** Sales, marketing, operations, the site, the inbox. Each agent has a job. You do not assemble a stack of bots.
- **Tools connect the same way.** Gmail, the calendar, GitHub, a custom server. Integrations is the only door, so the team and the people know where to go.
- **Nothing important happens in secret.** A routine waits until you approve it. A change on your computer waits until you allow that exact file or command.
- **The terminal is the same account.** Install the program, run `allin1`, and type. `/login` signs you into allin1app.com. `/folder` picks the folder this computer may use.

The app, the subscription, and your data live at [allin1app.com](https://allin1app.com). This page is how you put Allin1 on a computer.

## On your computer in a minute

Windows, in PowerShell:

```powershell
irm https://allin1app.com/install.ps1 | iex
```

Mac and Linux:

```sh
curl -fsSL https://allin1app.com/install.sh | sh
```

Open a new terminal:

```sh
allin1
```

Type a sentence. It goes to your agent, and the same chat is in Agent Hub under Terminal.

| Command | What it does |
| --- | --- |
| `/login` | Opens allin1app.com and connects one location |
| `/folder` | Chooses the folder agents may use on this computer |
| `/update` | Replaces the program when a newer one is ready |
| `/help` | The rest |

`/update` replaces the program file only. The folder you granted and the sign-in on this machine stay where they are.

A subscription is required before the program signs in. Without one, the browser opens pricing and Allin1 stays signed out.

## The install is checked

The program is downloaded over HTTPS from allin1app.com. Its SHA-256 checksum is checked before anything is kept. If the file and the checksum disagree, the download is deleted and nothing is installed. If this computer cannot check the file, the install stops.

The installer writes one program into your user folder and adds that folder to your user Path. It does not ask for an administrator password. It does not touch the folders you later choose with `/folder`.

Read the installer before you run it, if you want to see every line:

```powershell
irm https://allin1app.com/install.ps1
```

```sh
curl -fsSL https://allin1app.com/install.sh
```

## Start

**[Create the account at allin1app.com](https://allin1app.com)**

Then come back to the terminal and run `allin1`.

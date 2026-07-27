I am a full stack engineer with a builder on the side. I mostly write agent infrastructure and the interfaces that sit on top of it, in Python and TypeScript.

I work at [Agno](https://agno.com) as a design engineer on the core platform for creating and managing agents.

I also built and open sourced [agent-ui](https://github.com/agno-agi/agent-ui), Agno's chat interface for agents, a Next.js, TypeScript and TailwindCSS template that teams fork as the front end for their own agents. It sits at 1.8k stars and close to 400 forks.

Most of my side projects come out of problems I hit while doing that work.

[nst](https://github.com/anuragts/nst) came out of being fed up with Git worktrees. Running a few agents in parallel meant a worktree each, and the moment one had a branch checked out I could not check that same branch out in my main repo. Git just refuses. So I would sit there juggling directories and remembering which agent had claimed what. nst gives coding agents copy-on-write workspaces instead: every agent gets an isolated checkout instantly, nothing is recloned, and my main repo stays mine. I wrote up the whole thing [here](https://anrg.lol/writing/nst).

[hostplan](https://github.com/anuragts/hostplan) came from wanting my coworkers and friends to review a plan before I let an agent implement it. Plans used to live in a scratch file on my machine where nobody could see them. Now an agent adds a plan, gets back a URL, and that URL is both the thing I send a person for review and the thing another agent reads, so plans move between remote agents the same way they move between people. It opens straight in Codex, Claude Code, or Cursor.

[circle](https://github.com/anuragts/circle) is a real-time reactive database engine built around queries that stay live, so you write once and everything subscribed updates on its own.

Before those there was [tangerine](https://github.com/anuragts/tangerine), an in-memory vector database written in Java, and [tokenmaxxing](https://github.com/anuragts/tokenmaxxing), a native iPhone app and widget set for tracking Codex and Claude usage limits.

I write about what I'm building at [anrg.lol](https://anrg.lol).

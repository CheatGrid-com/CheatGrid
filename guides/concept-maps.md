# 🕸️ Concept Maps

Every cheat sheet on CheatGrid is one of two kinds:

- **💡 Concepts** explain how something works, whatever you build it with: RAG, OAuth, Scrum, observability.
- **🛠️ Tools** cover one language, library or product: Python, Docker, LangChain, Jira.

The **Concept Maps** join the two. Each concept is linked to the tools that put it to work, and each tool to the ideas underneath it. Learned RAG? The tools that do it are one click away. Picking up Kubernetes? So are the ideas it's built on. The maps grow on their own: when a new cheat sheet arrives, it shows up on the maps with its links.

Open **Concept Maps** from the top menu, right after Cheat Sheets.

## Two kinds of page

- **The main Concept Maps page** shows how whole categories connect, as one network with a node for each category. A line means the two categories' sheets pair up, their tools are used together (Pandas and NumPy with Python), or they simply cover much the same ground. **Hover a line** to see what's behind it, or click a category to see all its links with their reasons. Below the network you can explore one sheet at a time, see the most connected concepts and tools, and pick any category's map.
- **A category map** (DevOps, Generative AI, Data Engineering and the rest) lists every concept with its tools and every tool with its concepts, and opens with a big network of the whole category.

## Find any sheet, from any map

The search box at the top of every map page finds sheets **by name**, on any map. Start typing and suggestions drop down, each saying which map it lives on: type "redis" and you get **Redis · Tool · Databases map**. Pick one (click it, or use the arrow keys and **Enter**) and you land on that map with the sheet selected in the network, its links around it and its details open.

- **On a category map**, its own sheets come first (**On this map**), then matches from everywhere else (**Other maps**).
- **Whole maps** are suggested too: type "devops" to jump to the DevOps map.
- **Ctrl + click** (or **⌘ + click**) a suggestion opens it in a new tab.

While you type, the page underneath narrows to sheets whose **names** match, and the network lights them up. On the main page, only the categories that actually hold a match light up. Press **Esc** to close the suggestions and keep that view; **Clear** brings everything back.

## Text or Graph

The **Text / Graph** switch next to the search box decides how the cards show their links:

- **Graph** (the default) draws each card as a small network, with the sheet in the middle and its partners around it. Every node is a link: click one, the middle one too, to open that cheat sheet, and hover it for a quick summary.
- **Text** lists them as chips you can click.

Each card also has its own 🕸️ / ☰ button, so you can switch just one card. The site remembers your page-wide choice for next time.

**Ctrl + click** (or **⌘ + click** on a Mac) on any node, in a small graph or a big network, takes you to that sheet's own Concept Map instead: its category map showing **only that sheet**, in the middle of its own graph, and selected in the big network. The bar at the top says **Only** and the sheet's name; click its **×** (or start typing in the search box) to see everything again. Your Concepts / Tools choice stays as it was.

## The big network

Each category map opens with a network of all its sheets. The tools and ideas they link to from **other** categories sit around the edge in their own colours, so you can see where a field borrows from its neighbours.

- **Drag** any node to move it, and drag the background to pan.
- **Hold Ctrl (or ⌘) and scroll** to zoom, or use the **+** and **−** buttons. **Fit** brings the whole network back into view.
- **Click a node** to see its links in a card on the side. From there you can open the cheat sheet, centre the view on it, or jump to any of its partners.
- **Picking a sheet of this category also narrows the cards below the network to it**, marked **You are here**, so you can look at just that sheet and what surrounds it. The bar at the top says **Only** and its name. Press **Esc** (or click the empty background, or the **×**) to deselect it and see every card again.
- **Double click** a node to open its cheat sheet.
- **The legend** under the network names the colours. Hover a category to light it up, click it to keep it lit.
- **Expand** opens the network full-window for serious exploring. Press **Esc** to close it.

Not a fan of graphs? **Hide** turns the big networks off, and the site remembers that too. A **Show** button brings them back any time.

## Where two sheets meet

Every line between two sheets has a story, and you can read it. **Click any line on any map**: in the big networks, in a card's small graph, on a roadmap's network or in the strip on a cheat sheet. In a sheet's card, the **↔** next to each partner does the same. A window opens with the two side by side:

- **Best pairs:** entries of the two sheets side by side that show how they relate, whether or not they name each other, like Databricks' **MERGE INTO** beside the CDC sheet's **Delta Lake CDC MERGE**. Each pair says how strong it is: **Direct counterpart**, **Closely tied** or **Related**. They are picked for what they tell you about the link, not just for being alike, so shared ground every sheet has (security, logging) stays out, and a link shows a handful of good pairs rather than a long list.
- **Where they name each other:** the actual table rows where one sheet names the other, like the **RAG Chain** row in LangChain or the **Hybrid RAG** row in RAG. This is why the map links them. Each row links straight to its place in the sheet.
- **Explain this link:** a short AI explanation of how the two fit together. Which part of the idea each piece of the tool handles, one real case walked through step by step, what the tool still leaves up to you, and which rows to read next. It uses your usual [Explain](ai-explanations.md) allowance.

A pair that uses the same name on both sides (Vacuum in each sheet) is tagged **Same term in both**: you see what the idea says about it next to what the tool says. The best pairs are also drawn side by side, the concept sheet on the left and the tool on the right: a bigger dot is closer in meaning, a thicker line a stronger pair, a dashed line the same term in both, clicking a dot shows just its pairs and clicking a line picks that one pair. Every pair has **Explain this pair**: the idea behind it, then how the tool does it, with an example.

**Getting back is always one step.** Your browser's **Back** button (or the window's own **Back** button, or Esc) closes it and leaves you exactly where you were, card and all. The window has its own address, so you can share a link to it too. And when you open a cheat sheet from a map and press Back, the map comes back with that sheet still selected.

**Jump straight to the row.** Click a sheet's name in a pair (or in the window's title) and the cheat sheet opens with that row first, right under the table's header, so you can keep reading around it. Back brings you to the window again.

A free sheet shows every row. On a paid sheet you see the rows its own page already shows everyone, and the rest are named by section until you have a plan that includes it. A locked row in a pair has its own **Unlock** button, which goes straight to the plan that opens that sheet. **Explain this pair** needs both rows, so when one is locked for you the button says which plan it needs and takes you to the pricing page. On the main page's category network, a line joins two whole categories: click it to see why they're linked, and the reasons listed there open the same window for the sheets behind them.

## Explore one sheet at a time

On the main page, pick a concept or a tool (or type its name in the search box) and the explorer centres on it. Click any of its partners to keep going: every click re-centres the view, and a trail at the top brings you back the way you came. Switch to **Graph** and you walk it as a network instead, with each partner's own best links around it.

## Share any view

Every network, card and explorer view has a **Share** button. It copies a link that opens exactly what you're looking at: the network with the same sheet selected, one card drawn as a graph, or the explorer centred on a sheet.

## On roadmaps and cheat sheets too

You don't have to visit the maps to use them:

- **On a cheat sheet**, the strip under the title names its partners and shows them as a small network right there, every node a link.
- **On a roadmap**, every step has a **Map** button that does the same for that step, and **This roadmap as a network** shows the whole roadmap as one network: its steps coloured by section, the links between them, and the outside sheets that tie several steps together. Click a step's node and **Go to step** takes you straight to it.

## XP for exploring

Signed in, the maps earn XP in two ways:

- **Time:** **1 XP for every active minute** on a Concept Maps page, the same as reading a cheat sheet. It only counts while you're really on the page, pausing when you switch tabs or step away.
- **New sheets:** your first deliberate look at a sheet on a map earns a bonus: picking its node in a network, centring the explorer on it, or opening its graph on a card or a roadmap step. Each sheet pays once, up to a daily limit, and you'll see a small **+1 XP** where you earned it. Explore enough different sheets and you reach milestones, from **First steps** to **Atlas**, each worth a bonus.

Exploring counts toward your **[streak](streaks.md)** too: **10 active minutes** on the maps in a day earns that day's streak point, just like reading cheat sheets or clearing a flashcard session.

Your progress lives in two places:

- **[Stats](stats.md)** has a **Concept Maps** tab: how many sheets you've explored, your time on the maps, how much of each category's map you've covered (concepts and tools separately), and how far you are from the next milestone.
- Your **[Dashboard](dashboard.md)** shows the headline numbers and where you've explored most.

## Free for everyone

The maps are free to explore on every plan, signed in or not. The cheat sheets they link to keep their own plan, so a sheet you open from a map works exactly as it does anywhere else. Click a sheet you don't have yet and its card tells you what's inside (its tables, concepts, flashcards and practice questions) and which plan opens it; a free sheet is marked **Free**.

---

← Back to the [guides](README.md) · Read about **[Cheat Sheets](cheat-sheets.md)** and **[Roadmaps](roadmaps.md)**

+++
date = "2016-11-05T19:41:01+05:30"
title = "React-Chess"
draft = false
image = "portfolio/reactchess/cover.jpg"
showonlyimage = false
weight = 1
+++

<p>
<a href="https://deep-subs.herokuapp.com/" target="_blank"><strong>React-Chess</strong></a> was born from the love of the game. This is going to be under constant development as I learn to optimize the AI, get better at the game and just build beautiful UI. If you have the love for chess or programming in general, I'd love to chat!
</p>

[**GitHub source code**](https://github.com/Phongtlam/DeepSubs)
<div><a href="https://deep-subs.herokuapp.com/" target="_blank"><img src="/myjourney/portfolio/reactchess/welcome.jpg"></a></div>

## Project Overview

- Real time chess with unique room ID
- Basic AI using minimax game theory and algorithm
- AI calculations are being done server side and client inputs are being handled through React/Redux for better user experience
- Utilize React/Redux for components' reusability
- Bootstrap and CSS3/Sass to create responsive UI
- Routing via React-router V.4
- Passport.JS and O-Auth standard
- Socket.Io for real-time communications between clients and server
- PostgreSQL and Knex.JS for data migration and storage

<br>

<div class="reactchess"><img src="/myjourney/portfolio/reactchess/techstack.jpg"></div>
<div class="reactchess"><img src="/myjourney/portfolio/reactchess/thumb.jpg"></div>

<br>

### Minimax algorithm

> [Game theory](https://en.wikipedia.org/wiki/Game_theory) is "the study of mathematical models of conflict and cooperation between intelligent rational decision-makers."

DeepSubs Chess AI is built on this idea. Utilized minimax algorithm, the system essentially uses backtracking to determine the best move possible, at a given board configuration, given zero knowledge of how the opponent will proceed. The basis of game theory addresses zero-sum games. When one player makes a move, that results in a negative outcome for the other.

Every piece has an associated value given at the start of the game. Each piece also has its own 'board', with different values dictating movements throughout the game.

> **Improvements:** the pieces should swap new boards to accommodate for end game layouts.

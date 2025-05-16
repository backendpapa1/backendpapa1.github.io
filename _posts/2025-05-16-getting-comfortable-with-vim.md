---
title: Getting Comfortable with Neovim and Lua
date: 2025-05-16
layout: post
---

# Getting Comfortable with Neovim and Lua

Hey everyone, Paul here again.

It’s another day of progress in my systems development journey, and today I realized I really need to dedicate solid time to learning **Lua**. It's a bit daunting, but I’m not in a rush—I want to enjoy the process and build a strong foundation. Rushing would only mean scraping the surface and ending up as a half-baked systems developer.

## Learning Neovim the Right Way

At the moment, I’m using the built-in **Neovim Tutor** to get familiar with the environment—and I’ve already learned quite a lot! Here's a quick summary of some key commands and movements I've picked up:

### Basic Movement (Normal Mode)

- `l` – move right  
- `h` – move left  
- `j` – move down  
- `k` – move up  

Arrow keys also work for UP, DOWN, LEFT, RIGHT—but I’m trying to train myself on the Vim-native controls.

### Useful Commands

- `i` – insert text **before** the cursor  
- `A` – append text **after** the cursor  
- `x` – delete character under the cursor  
- `dw` – delete a word (cursor at the beginning)  
- `d$` – delete to the end of the line from the cursor  
- `:q!` – quit Neovim **without saving**  
- `:wq` – write to file and quit  
- `nvim filename.extension` – open (or create) a file in Neovim  

There’s still a lot to learn, but I’m making steady progress.

## Current Goals

```javascript
console.log("Get comfortable with Neovim!");
console.log("Learn how Lua programming works");

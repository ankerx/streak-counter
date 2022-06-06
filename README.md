# `@ankerx/streak-counter streak-counter

This is a basic streak counter - inspired by Duolingo - written in TypeScript and meant for the browser (uses `localStorage`).

## Install

```shell
yarn add @ankerx/streak-counter
npm install @ankerx/streak-counter
```

## Usage

```import {streakCounter} from '@jsjoeio/streak-counter'

const today = new Date()
const streak = streakCounter(localStorage, today)
// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "11/11/2022",
//    startDate: "11/11/2022",
// }
```

# FinSprint – Gamified Financial Learning & Virtual Trading Platform

Target Audience: Gen Z (India)

Platform: Responsive Web App (Mobile & Desktop)

Currency: Indian Rupee (₹)


## Overview

FinSprint is a gamified financial literacy and virtual trading platform designed specifically for Indian Gen Z youth. Inspired by platforms like Duolingo, Robinhood, and Acorns, the app transforms complex financial concepts into simple, engaging daily habits

Users start with a virtual investment portfolio of ₹1,00,000 and participate in a 30-day investment sprint, where they learn to navigate the stock and crypto markets without risking real money

With progressive asset unlocking, AI-driven mentorship, bite-sized financial news, and risk-adjusted leaderboards, the platform empowers young investors to build real-world wealth-creation skills before investing actual money


## Core Features


### 1. Gamified Learning Hub (Duolingo-style learning)

Bite-Sized Daily Quizzes

Users receive 2 financial literacy questions per day

Correct answers → earn points

Wrong answers → instant explanation for learning

Daily Streaks

#### Tracks continuous activity:
Quiz completion

Trading activity

Daily login

#### Maintaining streaks gives:
Bonus points

Virtual currency multipliers

Progressive Difficulty Unlocking

Assets unlock as the user gains experience


#### Level 1 (Default Access)

Gold

Stocks (Equities)

#### Level 2 (Unlocked with progress)

Cryptocurrencies

Alternative assets

This system ensures beginners are protected from high volatility early on


### 2. Virtual Trading Simulator (30-Day Investment Sprint)
The ₹1 Lakh Challenge

Each user receives:

#### ₹1,00,000 virtual money

Users can experiment with investments across multiple assets for 30 days.

Buy/Sell Execution Engine


#### A frictionless trading interface that allows users to:

Buy assets

Sell assets

Track order execution

Manage virtual portfolio


#### Supported assets include:

Stocks

Mutual Funds

Cryptocurrency

Digital Gold & Silver

Risk-Adjusted Scoring System

#### On Day 31, portfolios are evaluated based on:

Profit

Risk management

Diversification

Asset Risk Weights

A diversified portfolio earns a higher skill score than one that takes extreme risks


## 3. Portfolio & Investment Tracker

Real-Time Portfolio Dashboard


#### Users can view:

Current asset allocation

Investment value

Portfolio performance

Trend Analysis


#### Interactive graphs display:

Historical asset performance

Investment growth

Market movement

Live Sell Valuations


#### Users can instantly see:

What they would earn if they sold assets at the current market price

This reflects real-world market spreads and price fluctuations



## 4. Market Insights & Financial News
Asset Learning Pages

#### Each asset category includes:

Trend graphs

Market indicators

Beginner-friendly explanations

#### Trend indicators include:

Bullish → upward trend

Bearish → downward trend

Inshorts-Styled Financial Feed , inspired by Inshorts

#### Daily financial news summarized into 60 words

This helps users connect real-world events with market movement


## 5. Social & AI Features
Dynamic Leaderboards


#### Users compete with friends across multiple categories:

Highest net profit

Best risk-adjusted score

Longest daily streak

Best diversified portfolio

AI Financial Mentor


#### An integrated chatbot available 24/7 that can:

Explain financial terms

Answer user questions

Provide investment insights

Suggest diversification strategies


#### Database Strategy (MongoDB Atlas)

The platform uses MongoDB Atlas, which fits perfectly with the application's dynamic data requirements


#### User Profiles Stores:

User information

Streak data

Quiz history

Asset unlock levels

30-day sprint progress

MongoDB allows nested document structures, making complex user state easy to manage

#### Portfolio Tracking

Daily portfolio snapshots are stored in time-series collections, enabling:

Fast portfolio graphs

Historical investment analysis

Quiz Logs

#### Each user document contains:

Previously answered questions

Performance history

This ensures quiz questions are never repeated

# Tech Stack


## Frontend

React / Next.js

TailwindCSS

Chart.js / Recharts

## Backend

Node.js

Express.js

## Database

MongoDB Atlas

## Other Integrations

Market data APIs

AI chatbot APIs

# Key Goals

Improve financial literacy among Gen Z

Encourage safe investing habits

Make finance simple, interactive, and engaging

Help users practice investing before using real money


# Future Enhancements

Social trading (copy portfolios)

Real brokerage integration

AI portfolio risk analysis

Community investment challenges

Personalized financial learning paths

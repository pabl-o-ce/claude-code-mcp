# Introduction

> Learn how to use Cursor's core features: Tab completion, Chat for code queries, and Agent for assistance

## Overview

Cursor is a powerful AI-first code editor that enhances your development workflow. After [installation](/get-started/installation), you'll have access to these core features that work together seamlessly to make you more productive:

* **AI-powered code completion** that understands your codebase and provides context-aware suggestions
* **Conversation interface** for exploring, understanding, and modifying code with Ask, Edit, and Agent modes
* **Intelligent tools** for handling complex development tasks

## Getting Started

Start exploring Cursor's AI-powered features:

* **Tab**: Press `Tab` for intelligent code completions
* **CMD-K**: Use `Cmd/Ctrl + K` for inline code edits
* **Composer**: Use `⌘I` to open the unified AI interface with Ask, Edit, and Agent modes

## Settings

Cursor is designed to be flexible and customizable. You can configure it in two ways:

### Cursor Settings

* Access via gear icon, `Cmd/Ctrl + Shift + J`, or Command Palette > `Cursor Settings`
* Configure AI features and Cursor-specific preferences

### Editor Settings

* Access via Command Palette (`Cmd/Ctrl + Shift + P`) > `"Preferences: Open Settings (UI)"`
* Adjust editor behavior and appearance

Let's explore each feature in detail:

### Tab

Tab completion in Cursor is powered by advanced AI models that understand your code context. As you type, you'll receive intelligent suggestions that:

* Complete your current line of code
* Suggest entire function implementations
* Help with common patterns and boilerplate
* Adapt to your coding style over time

Learn more about [Tab features](/tab/overview) or see how it [compares to GitHub Copilot](/tab/from-gh-copilot).

### Composer

Cursor provides a unified AI interface with three modes that seamlessly work together:

**Ask Mode**

* Ask questions about specific code sections
* Get explanations of complex functions
* Find code patterns and examples
* Discover and understand your codebase

**Edit Mode**

* Make single-turn edits to your code
* Apply targeted changes with precision
* Review and apply changes with confidence
* Work with files individually

**Agent Mode (Default)**

* Make codebase-wide changes and refactoring
* Implement new features from requirements
* Debug complex issues across multiple files
* Generate tests and documentation
* Maintain consistency across your entire project

Switch between modes during conversations to best suit your current task. Learn more about the [unified AI interface](/composer) or explore specific capabilities in [Agent mode](/agent).

### Context

Context is the foundation that powers all of Cursor's AI features. Here's how it works:

* When you open a codebase, we automatically [index your code](/context/codebase-indexing) to make it available as context
* Use [@-symbols](/context/@-symbols/basic) to precisely control what context you provide:
  * [@files](/context/@-symbols/@-files) and [@folders](/context/@-symbols/@-folders) for specific paths
  * [@web](/context/@-symbols/@-web) for external documentation
  * [@git](/context/@-symbols/@-git) for version control context
* Configure [rules for AI](/context/rules-for-ai) to customize behavior
* Set up [MCP](/context/model-context-protocol) for external context providers

## Models

You can see all the models we support and their pricing on the [models page](/settings/models). Configure your [API keys](/settings/api-keys) and [preferences](/settings/preferences) in Settings.

## Usage

It's highly recommended to read about [usage](/account/usage) and [plans](/account/plans) to understand how Cursor pricing works. Check out our [pricing page](/account/pricing) for more details about plans and features.

Need help? Visit our [troubleshooting guide](/troubleshooting/troubleshooting-guide) or join our [community forum](/resources/forum).

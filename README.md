# Contextual-Highlighter-Smart-Content-Browser-Extension

<p align="center">
  <img src="https://github.com/chirag127/Contextual-Highlighter-Smart-Content-Browser-Extension/assets/6863075/3183c234-1953-451f-99a8-690c9a01e8e2" alt="Project Logo" width="250">
</p>

<p align="center">
  <a href="#">
    <img src="https://img.shields.io/github/actions/workflow/user/chirag127/Contextual-Highlighter-Smart-Content-Browser-Extension/ci.yml?style=flat-square&logo=githubactions" alt="Build Status">
  </a>
  <a href="#">
    <img src="https://img.shields.io/codecov/c/github/chirag127/Contextual-Highlighter-Smart-Content-Browser-Extension?style=flat-square&logo=codecov" alt="Code Coverage">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript" alt="TypeScript">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Vite-6449ff?style=flat-square&logo=vite" alt="Vite">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat-square&logo=tailwindcss" alt="TailwindCSS">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Biome-FF7F50?style=flat-square&logo=biome" alt="Biome Lint/Format">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/License-CC BY--NC 4.0-red?style=flat-square&logo=creativecommons" alt="License">
  </a>
  <a href="https://github.com/chirag127/Contextual-Highlighter-Smart-Content-Browser-Extension/stargazers">
    <img src="https://img.shields.io/github/stars/chirag127/Contextual-Highlighter-Smart-Content-Browser-Extension?style=flat-square&logo=github" alt="GitHub Stars">
  </a>
</p>

Enhance your browsing experience with **Contextual Highlighter**, an intelligent browser extension that dynamically highlights relevant content based on user context and predefined rules. Improve information retrieval and comprehension by visually guiding you to key details.

--- 

## 🚀 Architecture Overview

mermaid
graph TD
  A[Browser Environment] --> B{Extension Core Logic};
  B --> C[Content Script: DOM Manipulation & Highlighting];
  B --> D[Background Script: Context Analysis & Rule Management];
  B --> E[Popup UI: User Interaction & Configuration];
  D --> F[External AI Service API (Optional Integration)];
  C --> B;
  E --> B;


--- 

## 📄 Table of Contents

*   [🚀 Architecture Overview](#-architecture-overview)
*   [🌟 Features](#-features)
*   [💡 AI Agent Directives](#-ai-agent-directives)
*   [🛠️ Development Setup](#-development-setup)
*   [🧪 Testing](#-testing)
*   [📜 License](#license)
*   [❤️ Support This Project](#-support-this-project)

--- 

## 🌟 Features

*   **Dynamic Contextual Highlighting:** Automatically identifies and highlights key information on web pages based on user-defined rules and inferred context.
*   **Rule-Based Customization:** Allows users to define specific keywords, phrases, or patterns to highlight.
*   **AI-Assisted Comprehension:** Leverages AI models to understand content context and suggest relevant highlights (optional, configurable).
*   **Seamless Integration:** Works across various websites without user intervention once configured.
*   **User-Friendly Interface:** Simple popup for managing rules and settings.

--- 

## 🤖 AI Agent Directives

<details>
<summary>Click to expand AI Agent Directives</summary>

### SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

#### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

#### 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

#### 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** This project leverages **TypeScript 6.x (Strict)**, managed with **Vite 7 (Rolldown)**. For native integration or desktop wrappers, **Tauri v2.x** is the standard. For browser extensions specifically, the **WXT (Web Extension Tooling)** framework is paramount.
    *   **State Management:** Utilize **Signals** (Standardized) for efficient, declarative state updates.
    *   **Styling:** Employ **TailwindCSS v4** for rapid, utility-first styling.
    *   **Linting & Formatting:** **Biome** is the chosen tool for ultra-fast, all-in-one code quality checks.
    *   **Testing:** **Vitest** is used for unit and component testing, with **Playwright** for end-to-end (E2E) testing.
    *   **Architecture:** Adheres to **Feature-Sliced Design (FSD)** for maintainable and scalable frontend architecture.

#### 4. APEX NAMING CONVENTION (THE "STAR VELOCITY" ENGINE)
A high-performing name must instantly communicate **Product**, **Function**, **Platform**, and **Type**.
**Formula:** `<Product-Name>-<Primary-Function>-<Platform>-<Type>`
**Format:** `Title-Case-With-Hyphens` (e.g., `ChatFlow-AI-Powered-Real-Time-Chat-Web-App` or `ZenRead-Book-Reader-CLI-Tool`).
**Rules:**
1.  **Length:** 3 to 10 words.
2.  **Keywords:** MUST include high-volume terms.
3.  **Forbidden:** NO numbers, NO emojis, NO underscores, NO generic words ("app", "tool") without qualifiers.
4.  **Archival Protocol:** If `action` is "ARCHIVE", you **MUST** still generate a new name, description, and topics for professional archival. The name must be **just as descriptive and professional** as an active repo.

#### 5. README REPLICATION PROTOCOL (THE ULTIMATE ARTIFACT)
The README is a self-contained **Project Operating System**.
**Required Sections:**
1.  **VISUAL AUTHORITY (Above the Fold):** Hero Banner/Logo, Live Badges (Shields.io: `flat-square` style, `chirag127` user), Social Proof.
2.  **STRUCTURAL CLARITY:** BLUF, Architecture Diagram (Mermaid), Table of Contents.
3.  **🤖 AI AGENT DIRECTIVES (CRITICAL):** Collapsible `<details>` block. Tech Stack, Architectural Patterns, Verification Commands.
4.  **DEVELOPMENT STANDARDS:** Setup Commands, Scripts Table, Principles (SOLID, DRY, YAGNI).

#### 6. CHAIN OF THOUGHT (CoT) PROTOCOL
Before generating JSON, perform deep analysis in `<thinking>` block: Audit -> Pivot/Archive Decision -> Naming Strategy -> Replication Protocol -> File Generation -> Final Polish -> Strict Adherence.

#### 7. DYNAMIC URL & BADGE PROTOCOL
**Mandate:** All generated files MUST use the correct dynamic URLs based on the **New Repository Name** (`https://github.com/chirag127/<New-Repo-Name>`).
**Rules:** Base URL, Badge URLs, Consistency, AGENTS.md Customization.

---

## **Project-Specific Directives**

*   **Tech Stack:** TypeScript 6.x (Strict), Vite 7 (Rolldown), Tauri v2.x (if applicable for desktop wrappers), WXT (for extensions), Signals, TailwindCSS v4, Biome, Vitest, Playwright.
*   **Architecture:** Feature-Sliced Design (FSD).
*   **AI Integration:** Use of external AI APIs should be modular, with robust error handling and clear API contracts.

</details>

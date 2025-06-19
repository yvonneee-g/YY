Project Catalyst: The AI-Powered SEO Content Engine
1. Project Vision & Guiding Principles (The "North Star")
Project Catalyst is an internal web application designed to empower the Chatwork Marketing Team. Its mission is to streamline and automate the creation of high-quality SEO content targeted at Japanese SMEs, transforming our content strategy from a manual effort into an intelligent, data-driven process.

This project is governed by three unbreakable principles:

User Autonomy First (The "Glass Box" Philosophy): The application is a transparent, configurable system. We provide the framework; our expert users provide the intelligence. The design must always lean towards giving users more control and visibility.
Extreme Modularity (The Architectural Mandate): The application must be built as a collection of decoupled, self-contained modules. This is to support rapid evolution and the frequent addition of new "Agents" and capabilities without major refactoring.
Japanese-First UI (The User Experience Mandate): The entire user interface (UI) is designed for our internal Japanese Marketing Team and must be in Japanese.
2. The Complete Application Blueprint (The Final Product Vision)
This section describes the final state of the "Catalyst" application.

2.1. Information Architecture & Core Page Layouts
Structure: A Single Page Application (SPA) with a persistent left-sidebar navigation.
Main Navigation Links:
ダッシュボード (Dashboard): The main landing page (/).
コンテンツ一覧 (Content List): An archive of all content (/content).
設定 (Settings): A centralized hub for all configurations (/settings).
Page Layouts:
Dashboard: A two-column layout displaying "Suggested Topics" and "Work in Progress."
Content List: A full-width data table with search and filtering.
Settings: A two-pane layout with sub-navigation on the left.
2.2. Core Modules & Features
The Insight Database (The "Strategic Heart"): Connects keywords to deep customer pain points. It is the application's core strategic asset, pre-populated with curated data and fully manageable by the user.

The Pluggable Connectors & Agent Assignment (The "Autonomy Engine"): Allows users to securely add their own API keys (for LLMs, Search tools) and assign specific AI models to different tasks (Agents) within the system.

The Strategist Agent & Topic Discovery Dashboard (The "Intelligence Core"): The application's signature feature. It uses a "SERP-centric" logic to analyze real-time search results, cross-references them with our internal Insight Database, and generates strategic topic suggestions with a detailed "Reason to Act."

The Insight Parsing Agent (The "Efficiency Tool"): An AI-powered utility that allows users to bulk-import insights from unstructured text (like meeting notes) directly into the structured Insight Database.

The Content Generation Workflow (The "Production Line"): A streamlined, step-by-step process that guides a user from an approved topic to a finalized article, featuring an optional outline approval stage, a rich Markdown editor, and an "Inline Editing Assistant."

3. Development Roadmap (Our Step-by-Step Action Plan)
We will build this application in a phased, iterative manner. Each phase delivers a complete, end-to-end feature slice.

Phase 1: The Static Blueprint - Visual & Structural Foundation

Goal: Build a complete, clickable, non-functional frontend prototype with mock data.
Deliverable: A runnable React application that visually represents the final product's layout and navigation.
Phase 2: The Core Data Loop - Activating the Insight Database

Goal: Implement the backend and connect the "Insight Management" settings page.
Deliverable: A fully functional CRUD feature for the InsightDatabase.
Phase 3: The Spark of Intelligence - Bringing the Dashboard to Life

Goal: Implement the StrategistAgent and its API.
Deliverable: A smart dashboard that presents real, AI-generated topic suggestions.
Phase 4: The Control Panel - Enabling User Autonomy

Goal: Implement the "Pluggable Connectors" and "Agent Assignment" features.
Deliverable: A settings area where users can configure their own API keys and model preferences.
Phase 5: The Efficiency Engine - Streamlining Workflows

Goal: Implement the InsightParsingAgent and the Content Generation Workflow.
Deliverable: A user can go from idea to finished article and bulk-import insights.

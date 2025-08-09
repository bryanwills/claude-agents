# Contains Studio AI Agents

A comprehensive collection of specialized AI agents designed to accelerate and enhance every aspect of rapid development. Each agent is an expert in their domain, ready to be invoked when their expertise is needed.

## 📥 Installation

1. **Download this repository:**
   ```bash
   git clone https://github.com/bryanwills/claude-agents
   ```

2. **Copy to your Claude Code agents directory:**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```

   Or manually copy all the agent files to your `~/.claude/agents/` directory.

3. **Restart Claude Code** to load the new agents.

## 🚀 Quick Start

Agents are automatically available in Claude Code. Simply describe your task and the appropriate agent will be triggered. You can also explicitly request an agent by mentioning their name.

📚 **Learn more:** [Claude Code Sub-Agents Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### Example Usage
- "Create a new app for tracking meditation habits" → `rapid-prototyper`
- "What's trending on TikTok that we could build?" → `trend-researcher`
- "Our app reviews are dropping, what's wrong?" → `feedback-synthesizer`
- "Make this loading screen more fun" → `whimsy-injector`

## 📁 Directory Structure

Agents are organized by department for easy discovery:

```
agents/
├── bonus/
│   ├── joker.md
│   ├── legal-advisor.md
│   ├── mermaid-expert.md
│   └── studio-coach.md
├── design/
│   ├── brand-guardian.md
│   ├── ios-developer.md
│   ├── mobile-developer.md
│   ├── sql-pro.md
│   ├── typescript-pro.md
│   ├── ui-designer.md
│   ├── ui-engineer.md
│   ├── ui-ux-designer.md
│   ├── ux-researcher.md
│   ├── visual-storyteller.md
│   └── whimsy-injector.md
├── engineering/
│   ├── ai-engineer.md
│   ├── api-designer.md
│   ├── api-documenter.md
│   ├── backend-architect.md
│   ├── backend-typescript-architect.md
│   ├── blockchain-developer.md
│   ├── build-engineer.md
│   ├── cloud-architect.md
│   ├── csharp-developer.md
│   ├── data-analyst.md
│   ├── data-engineer.md
│   ├── data-researcher.md
│   ├── data-scientist.md
│   ├── database-admin.md
│   ├── database-optimizer.md
│   ├── deployment-engineer.md
│   ├── devops-automator.md
│   ├── docs-architect.md
│   ├── documentation-engineer.md
│   ├── dx-optimizer.md
│   ├── electron-pro.md
│   ├── embedded-systems.md
│   ├── fintech-engineer.md
│   ├── frontend-developer.md
│   ├── fullstack-developer.md
│   ├── game-developer.md
│   ├── git-workflow-manager.md
│   ├── golang-engineer.md
│   ├── graphql-architect.md
│   ├── graphql-optimizer.md
│   ├── iot-engineer.md
│   ├── java-architect.md
│   ├── javascript-engineer.md
│   ├── knowledge-synthesizer.md
│   ├── legacy-modernizer.md
│   ├── llm-architect.md
│   ├── machine-learning-engineer.md
│   ├── microservices-architect.md
│   ├── ml-engineer.md
│   ├── mlops-engineer.md
│   ├── mobile-app-builder.md
│   ├── network-engineer.md
│   ├── nextjs-developer.md
│   ├── nlp-engineer.md
│   ├── payment-integration.md
│   ├── platform-engineer.md
│   ├── postgres-pro.md
│   ├── prompt-engineer.md
│   ├── python-backend-engineer.md
│   ├── quant-analyst.md
│   ├── rapid-prototyper.md
│   ├── react-specialist.md
│   ├── refactoring-specialist.md
│   ├── reference-builder.md
│   ├── risk-manager.md
│   ├── rust-engineer.md
│   ├── search-specialist.md
│   ├── spring-boot-engineer.md
│   ├── sre-engineer.md
│   ├── terraform-engineer.md
│   ├── test-writer-fixer.md
│   ├── tooling-engineer.md
│   ├── tutorial-engineer.md
│   └── websocket-engineer.md
├── marketing/
│   ├── app-store-optimizer.md
│   ├── content-creator.md
│   ├── content-marketer.md
│   ├── context-manager.md
│   ├── customer-support.md
│   ├── growth-hacker.md
│   ├── instagram-curator.md
│   ├── market-researcher.md
│   ├── reddit-community-builder.md
│   ├── sales-automator.md
│   ├── tiktok-strategist.md
│   └── twitter-engager.md
├── product/
│   ├── business-analyst.md
│   ├── competitive-analyst.md
│   ├── feedback-synthesizer.md
│   ├── product-manager.md
│   ├── research-analyst.md
│   ├── sprint-prioritizer.md
│   ├── trend-analyst.md
│   └── trend-researcher.md
├── project-management/
│   ├── agent-organizer.md
│   ├── experiment-tracker.md
│   ├── multi-agent-coordinator.md
│   ├── project-manager.md
│   ├── project-shipper.md
│   ├── studio-producer.md
│   ├── task-distributor.md
│   └── workflow-orchestrator.md
├── studio-operations/
│   ├── analytics-reporter.md
│   ├── finance-tracker.md
│   ├── infrastructure-maintainer.md
│   ├── legal-compliance-checker.md
│   └── support-responder.md
└── testing/
    ├── accessibility-tester.md
    ├── api-tester.md
    ├── architect-reviewer.md
    ├── chaos-engineer.md
    ├── code-reviewer.md
    ├── compliance-auditor.md
    ├── debugger.md
    ├── devops-troubleshooter.md
    ├── error-coordinator.md
    ├── error-detective.md
    ├── incident-responder.md
    ├── penetration-tester.md
    ├── performance-benchmarker.md
    ├── performance-engineer.md
    ├── performance-monitor.md
    ├── qa-expert.md
    ├── security-auditor.md
    ├── senior-code-reviewer.md
    ├── test-automator.md
    ├── test-results-analyzer.md
    ├── tool-evaluator.md
    └── workflow-optimizer.md
```

## 📋 Complete Agent List

### Engineering Department (`engineering/`)
- **ai-engineer** - Integrate AI/ML features that actually ship
- **api-designer** - Create robust and scalable API designs
- **api-documenter** - Generate comprehensive API documentation
- **backend-architect** - Design scalable APIs and server systems
- **backend-typescript-architect** - Architect strongly typed backends with TypeScript
- **blockchain-developer** - Develop blockchain and smart contract solutions
- **build-engineer** - Optimize build systems and CI/CD pipelines
- **cloud-architect** - Design cloud-native architectures
- **csharp-developer** - Specialize in C# and .NET development
- **data-analyst** - Analyze data and create insights
- **data-engineer** - Build reliable data pipelines and ETL workflows
- **data-researcher** - Conduct data research and analysis
- **data-scientist** - Perform data analysis and build ML models
- **database-admin** - Manage schemas, backups, migrations, and access
- **database-optimizer** - Tune queries and indexes for performance
- **deployment-engineer** - Automate build, release, and rollout workflows
- **devops-automator** - Deploy continuously without breaking things
- **docs-architect** - Alias of documentation-engineer
- **documentation-engineer** - Owns IA, API references, style guides, tutorials; activation keywords: api-documenter, docs-architect, reference-builder
- **dx-optimizer** - Improve developer experience, tooling, and inner loops
- **electron-pro** - Specialize in Electron desktop app development
- **embedded-systems** - Develop embedded systems and firmware
- **fintech-engineer** - Build financial technology solutions
- **frontend-developer** - Build blazing-fast user interfaces
- **fullstack-developer** - Develop full-stack applications
- **game-developer** - Create games and interactive experiences
- **git-workflow-manager** - Manage Git workflows and branching strategies
- **golang-engineer** - Build reliable services and CLIs in Go
- **graphql-architect** - GraphQL schema, federation, N+1, subscriptions, caching; activation keyword: graphql-optimizer
- **graphql-optimizer** - Optimize GraphQL performance and queries
- **iot-engineer** - Develop IoT solutions and connected devices
- **java-architect** - Design Java-based architectures
- **javascript-engineer** - Ship high-quality JavaScript across the stack
- **knowledge-synthesizer** - Synthesize information from multiple sources
- **legacy-modernizer** - Modernize legacy systems and code
- **llm-architect** - Design large language model architectures
- **machine-learning-engineer** - Build ML systems and models
- **microservices-architect** - Design microservices architectures
- **ml-engineer** - Train, evaluate, and ship ML models to production
- **mlops-engineer** - Operate, monitor, and scale ML in production
- **mobile-app-builder** - Create native iOS/Android experiences
- **network-engineer** - Design secure, reliable network topologies
- **nextjs-developer** - Specialize in Next.js development
- **nlp-engineer** - Develop natural language processing solutions
- **payment-integration** - Implement Stripe/PayPal and recurring billing flows
- **platform-engineer** - Build developer platforms and tools
- **postgres-pro** - Specialize in PostgreSQL development
- **prompt-engineer** - Design prompts, evals, and safety guardrails for LLMs
- **python-backend-engineer** - Build Python services and APIs
- **quant-analyst** - Perform quantitative analysis
- **rapid-prototyper** - Build MVPs in days, not weeks
- **react-specialist** - Specialize in React development
- **refactoring-specialist** - Refactor and improve existing code
- **reference-builder** - Alias of documentation-engineer
- **risk-manager** - Manage technical and project risks
- **rust-engineer** - Build safe, high-performance services in Rust
- **search-specialist** - Implement search functionality
- **spring-boot-engineer** - Specialize in Spring Boot development
- **sre-engineer** - Manage site reliability engineering
- **terraform-engineer** - Define infrastructure as code with Terraform
- **test-writer-fixer** - Write tests that catch real bugs
- **tooling-engineer** - Build developer tools and utilities
- **tutorial-engineer** - Produce step-by-step developer tutorials
- **websocket-engineer** - Implement real-time communication

### Product Department (`product/`)
- **feedback-synthesizer** - Transform complaints into features
- **sprint-prioritizer** - Ship maximum value in 6 days
- **trend-researcher** - Identify viral opportunities

### Marketing Department (`marketing/`)
- **app-store-optimizer** - Dominate app store search results
- **content-creator** - Generate content across all platforms
- **content-marketer** - Plan campaigns and editorial calendars
- **context-manager** - Maintain brand context, tone, and messaging
- **customer-support** - Draft helpful responses, macros, and help center content
- **growth-hacker** - Find and exploit viral growth loops
- **instagram-curator** - Master the visual content game
- **market-researcher** - Analyze market trends and opportunities
- **reddit-community-builder** - Win Reddit without being banned
- **sales-automator** - Generate outreach, sequences, and collateral
- **tiktok-strategist** - Create shareable marketing moments
- **twitter-engager** - Ride trends to viral engagement

### Design Department (`design/`)
- **brand-guardian** - Keep visual identity consistent everywhere
- **ios-developer** - Build delightful native iOS apps with Swift/SwiftUI
- **mobile-developer** - Prototype and refine mobile UI flows quickly
- **sql-pro** - Design schemas and write optimized SQL
- **typescript-pro** - Level up TypeScript types, APIs, and patterns
- **ui-designer** - Design interfaces developers can actually build
- **ui-engineer** - Implement pixel-perfect, accessible UI components
- **ui-ux-designer** - Blend UX research with UI craft to ship usable designs
- **ux-researcher** - Turn user insights into product improvements
- **visual-storyteller** - Create visuals that convert and share
- **whimsy-injector** - Add delight to every interaction

### Project Management (`project-management/`)
- **agent-organizer** - Coordinate multi-agent workflows and task distribution
- **experiment-tracker** - Data-driven feature validation
- **multi-agent-coordinator** - Orchestrate complex multi-agent collaborations
- **project-manager** - Plan, track, and deliver projects on time
- **project-shipper** - Launch products that don't crash
- **studio-producer** - Keep teams shipping, not meeting
- **task-distributor** - Efficiently assign and track tasks across team members
- **workflow-orchestrator** - Design and optimize team workflows and processes

### Studio Operations (`studio-operations/`)
- **analytics-reporter** - Turn data into actionable insights
- **finance-tracker** - Keep the studio profitable
- **infrastructure-maintainer** - Scale without breaking the bank
- **legal-compliance-checker** - Stay legal while moving fast
- **support-responder** - Turn angry users into advocates

### Testing & Benchmarking (`testing/`)
- **accessibility-tester** - Ensure applications are accessible to all users
- **api-tester** - Ensure APIs work under pressure
- **architect-reviewer** - Review system architecture and design decisions
- **chaos-engineer** - Test system resilience through controlled chaos
- **code-reviewer** - Provide thorough code reviews and feedback
- **compliance-auditor** - Ensure compliance with industry standards and regulations
- **debugger** - Systematically isolate and fix defects
- **devops-troubleshooter** - Diagnose CI/CD and infrastructure issues
- **error-coordinator** - Coordinate error handling and incident response
- **error-detective** - Triage exceptions and trace root causes
- **incident-responder** - Handle on-call incidents quickly and safely
- **penetration-tester** - Identify security vulnerabilities through ethical hacking
- **performance-benchmarker** - Make everything faster
- **performance-engineer** - Optimize system performance and scalability
- **performance-monitor** - Monitor and analyze system performance metrics
- **qa-expert** - Ensure quality standards across development lifecycle
- **security-auditor** - Audit security practices and identify vulnerabilities
- **senior-code-reviewer** - Provide rigorous, actionable code reviews
- **test-automator** - Build reliable automated test suites
- **test-results-analyzer** - Find patterns in test failures
- **tool-evaluator** - Choose tools that actually help
- **workflow-optimizer** - Eliminate workflow bottlenecks

## 🎁 Bonus Agents
- **studio-coach** - Rally the AI troops to excellence
- **joker** - Lighten the mood with tech humor
- **legal-advisor** - Provide general legal guidance and risk framing (non-binding)
- **mermaid-expert** - Create clear system and process diagrams with Mermaid

## 🎯 Proactive Agents

Some agents trigger automatically in specific contexts:
- **studio-coach** - When complex multi-agent tasks begin or agents need guidance
- **test-writer-fixer** - After implementing features, fixing bugs, or modifying code
- **whimsy-injector** - After UI/UX changes
- **experiment-tracker** - When feature flags are added

## 💡 Best Practices

1. **Let agents work together** - Many tasks benefit from multiple agents
2. **Be specific** - Clear task descriptions help agents perform better
3. **Trust the expertise** - Agents are designed for their specific domains
4. **Iterate quickly** - Agents support the 6-day sprint philosophy

## 🔧 Technical Details

### Agent Structure
Each agent includes:
- **name**: Unique identifier
- **description**: When to use the agent with examples
- **color**: Visual identification
- **tools**: Specific tools the agent can access
- **System prompt**: Detailed expertise and instructions

### Adding New Agents
1. Create a new `.md` file in the appropriate department folder
2. Follow the existing format with YAML frontmatter
3. Include 3-4 detailed usage examples
4. Write comprehensive system prompt (500+ words)
5. Test the agent with real tasks

## 📊 Agent Performance

Track agent effectiveness through:
- Task completion time
- User satisfaction
- Error rates
- Feature adoption
- Development velocity

## 🚦 Status

- ✅ **Active**: Fully functional and tested
- 🚧 **Coming Soon**: In development
- 🧪 **Beta**: Testing with limited functionality

## 🛠️ Customizing Agents for Your Studio

### Agent Customization Todo List

Use this checklist when creating or modifying agents for your specific needs:

#### 📋 Required Components
- [ ] **YAML Frontmatter**
  - [ ] `name`: Unique agent identifier (kebab-case)
  - [ ] `description`: When to use + 3-4 detailed examples with context/commentary
  - [ ] `color`: Visual identification (e.g., blue, green, purple, indigo)
  - [ ] `tools`: Specific tools the agent can access (Write, Read, MultiEdit, Bash, etc.)

#### 📝 System Prompt Requirements (500+ words)
- [ ] **Agent Identity**: Clear role definition and expertise area
- [ ] **Core Responsibilities**: 5-8 specific primary duties
- [ ] **Domain Expertise**: Technical skills and knowledge areas
- [ ] **Studio Integration**: How agent fits into 6-day sprint workflow
- [ ] **Best Practices**: Specific methodologies and approaches
- [ ] **Constraints**: What the agent should/shouldn't do
- [ ] **Success Metrics**: How to measure agent effectiveness

#### 🎯 Required Examples by Agent Type

**Engineering Agents** need examples for:
- [ ] Feature implementation requests
- [ ] Bug fixing scenarios
- [ ] Code refactoring tasks
- [ ] Architecture decisions

**Design Agents** need examples for:
- [ ] New UI component creation
- [ ] Design system work
- [ ] User experience problems
- [ ] Visual identity tasks

**Marketing Agents** need examples for:
- [ ] Campaign creation requests
- [ ] Platform-specific content needs
- [ ] Growth opportunity identification
- [ ] Brand positioning tasks

**Product Agents** need examples for:
- [ ] Feature prioritization decisions
- [ ] User feedback analysis
- [ ] Market research requests
- [ ] Strategic planning needs

**Operations Agents** need examples for:
- [ ] Process optimization
- [ ] Tool evaluation
- [ ] Resource management
- [ ] Performance analysis

#### ✅ Testing & Validation Checklist
- [ ] **Trigger Testing**: Agent activates correctly for intended use cases
- [ ] **Tool Access**: Agent can use all specified tools properly
- [ ] **Output Quality**: Responses are helpful and actionable
- [ ] **Edge Cases**: Agent handles unexpected or complex scenarios
- [ ] **Integration**: Works well with other agents in multi-agent workflows
- [ ] **Performance**: Completes tasks within reasonable timeframes
- [ ] **Documentation**: Examples accurately reflect real usage patterns

#### 🔧 Agent File Structure Template

```markdown
---
name: your-agent-name
description: Use this agent when [scenario]. This agent specializes in [expertise]. Examples:\n\n<example>\nContext: [situation]\nuser: "[user request]"\nassistant: "[response approach]"\n<commentary>\n[why this example matters]\n</commentary>\n</example>\n\n[3 more examples...]
color: agent-color
tools: Tool1, Tool2, Tool3
---

You are a [role] who [primary function]. Your expertise spans [domains]. You understand that in 6-day sprints, [sprint constraint], so you [approach].

Your primary responsibilities:
1. [Responsibility 1]
2. [Responsibility 2]
...

[Detailed system prompt content...]

Your goal is to [ultimate objective]. You [key behavior traits]. Remember: [key philosophy for 6-day sprints].
```

#### 📂 Department-Specific Guidelines

**Engineering** (`engineering/`): Focus on implementation speed, code quality, testing
**Design** (`design/`): Emphasize user experience, visual consistency, rapid iteration
**Marketing** (`marketing/`): Target viral potential, platform expertise, growth metrics
**Product** (`product/`): Prioritize user value, data-driven decisions, market fit
**Operations** (`studio-operations/`): Optimize processes, reduce friction, scale systems
**Testing** (`testing/`): Ensure quality, find bottlenecks, validate performance
**Project Management** (`project-management/`): Coordinate teams, ship on time, manage scope

#### 🎨 Customizations

Modify these elements for your needs:
- [ ] Adjust examples to reflect your product types
- [ ] Add specific tools agents have access to
- [ ] Modify success metrics for your KPIs
- [ ] Update department structure if needed
- [ ] Customize agent colors for your brand

## 🤝 Contributing

To improve existing agents or suggest new ones:
1. Use the customization checklist above
2. Test thoroughly with real projects
3. Document performance improvements
4. Share successful patterns with the community

## 🔗 Related Repositories & Credits

This repository merges and adapts ideas and scripts from the following open-source projects. Huge thanks to the authors and communities behind them:

- [contains-studio/agents](https://github.com/contains-studio/agents) — Original agent structure, examples, and documentation patterns used as a foundation and reference.
- [wshobson/agents](https://github.com/wshobson/agents) — Additional agent scripts, formats, and ideas incorporated to create a more comprehensive set.
- [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) — Broader catalog used to align names, define merges, and identify capability gaps.

If you find this useful, please consider supporting and crediting the original work by starring their repositories.

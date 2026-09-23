![OReilly_logo_rgb.png](resources%2FOReilly_logo_rgb.png)

This repository contains the hands-on exercises for the O’Reilly Live Event:

# AI Agents Bootcamp – Designing and Deploying Enterprise Agentic Systems

## Repository Structure

```
.
├── hands_on/  # Hands-on exercises
├── helper_functions/  # Helper functions for some notebooks     
└── README.md
```

---

# Day 1 – Foundations and Multi-Agent Design

## 1. From Stateless LLM to Stateful Agent

**Concepts**

- State machines and typed state
- Tool integration in LangGraph
- Deterministic control flow

**Exercise**

Build a minimal stateful agent with one tool.


---

## 2. Structured Reasoning and Test-Time Intelligence

**Concepts**

- Chain of Thought and ReAct
- Planner–executor vs unified agents
- Test-time compute tradeoffs
- Error propagation and validation

**Exercise**

Compare a simple agent with a planner–judge setup.



---

## 3. Human-in-the-Loop Safeguards

**Concepts**

- Autonomy vs oversight
- Checkpointing and state inspection
- Interrupt and resume patterns

**Exercise**

Insert a human approval gate into your workflow.



---

## 4. From Single Agent to Multi-Agent System

**Concepts**

- Supervisor-based architectures
- Role separation
- Delegation and task routing

**Exercise**

Transform a single-agent workflow into a two-agent system.



---

## 5. Communication Patterns in MAS

**Concepts**

- Message passing vs shared memory
- Event-driven coordination
- Handoff reliability

**Exercise**

Swap a communication strategy and observe system behavior changes.



---

# Day 2 – Production-Ready Systems

## 6. Structured Data and MCP

**Concepts**

- Schema-based prompting
- Pydantic validation
- Model Context Protocol (MCP)

**Exercise**

Turn free-form input into validated structured tool calls.



---

## 7. Memory and Context Strategy

**Concepts**

- Episodic vs procedural memory
- Checkpointing
- Context engineering

**Exercise**

Add simple episodic and procedural memory to your agent.



---

## 8. Model and Architecture Tradeoffs

**Concepts**

- Planner vs unified agents
- Thinking vs non-thinking modes
- Dense vs MoE models
- KV cache considerations

**Exercise**

Switch planning modes and compare latency and decision quality.



---

## 9. Observability and Evaluation

**Concepts**

- Logging state transitions
- Monitoring workflows
- Task-specific evaluation

**Exercise**

Add logging hooks and compare two workflow runs.



---

## 10. Security and Guardrails

**Concepts**

- Tool misuse and memory poisoning
- Schema enforcement
- Secure execution patterns

**Exercise**

Add policy checks and validation to an existing workflow.




---

## Notebooks

Every notebook can be opened and run on Google Colab directly from the links below. Just click the **Open In Colab** badge next to the notebook you want to run. Notebooks are grouped by the day and session encoded in their filenames; `_SOLUTIONS` / `_solution` notebooks contain the completed versions of the corresponding exercises.

### Day 1 – Foundations and Multi-Agent Design

#### Session 1 — From Stateless LLM to Stateful Agent

**Demos**
| Notebook | Colab |
|---|---|
| LLM State | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DAY_1_SESSION_1_LLM_state.ipynb) |

#### Session 2 — Structured Reasoning and Test-Time Intelligence

**Hands-on**
| Notebook | Colab |
|---|---|
| Tree-of-Thought (ToT) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_1_HANDS_ON_SESSION_2_ToT.ipynb) |

#### Session 3 — Human-in-the-Loop Safeguards

**Demos**
| Notebook | Colab |
|---|---|
| Human-in-the-Loop (HITL) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DAY_1_DEMO_SESSION_3_HITL.ipynb) |

#### Session 4 — From Single Agent to Multi-Agent System

**Demos**
| Notebook | Colab |
|---|---|
| HITL Agent Workflow | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DAY_1_DEMO_SESSION_4_HITL_AGENT_WORKFLOW.ipynb) |
| HITL Agent Workflow — Solutions | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DAY_1_DEMO_SESSION_4_HITL_AGENT_WORKFLOW_SOLUTIONS.ipynb) |
| Hierarchical Agent Teams | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DAY_1_DEMO_SESSION_4_hierarchical_agent_teams.ipynb) |
| Swarms | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DAY_1_DEMO_SESSION_4_swarms.ipynb) |

**Hands-on**
| Notebook | Colab |
|---|---|
| Hierarchical Agent Teams | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_1_HANDS_ON_SESSION_4_hierarchical_agent_teams.ipynb) |
| Hierarchical Agent Teams — Solutions | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_1_HANDS_ON_SESSION_4_hierarchical_agent_teams_SOLUTIONS.ipynb) |
| Hierarchical Agent Teams — Solutions (Copy) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/Copy_of_DAY_1_HANDS_ON_SESSION_4_hierarchical_agent_teams_SOLUTIONS.ipynb) |

#### Session 5 — Communication Patterns in MAS

**Demos**
| Notebook | Colab |
|---|---|
| Communication Patterns | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/communication_patterns.ipynb) |

**Hands-on**
| Notebook | Colab |
|---|---|
| Communication Patterns Exchange — Solutions | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_1_HANDS_ON_communication_patterns_exchange_SOLUTIONS.ipynb) |

#### Other Day 1 Notebooks

**Hands-on**
| Notebook | Colab |
|---|---|
| Stakeholder Chaos to Structure | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_1_HANDS_ON_stakeholder_chaos_to_structure.ipynb) |
| Stakeholder Chaos to Structure — Solutions | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_1_HANDS_ON_stakeholder_chaos_to_structure_SOLUTIONS.ipynb) |
| Structured Spec with LangGraph — Solutions | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_1_HANDS_ON_structured_spec_langgraph_SOLUTIONS.ipynb) |
| LangGraph Web Search | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_1_HANDS_ON_langgraph_web_search.ipynb) |
| LangGraph Logging & Checkpointing — Solutions | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_1_HANDS_ON_langgraph_logging_checkpointing_SOLUTIONS.ipynb) |

### Day 2 – Production-Ready Systems

#### Session 2 — Memory and Context Strategy

**Hands-on**
| Notebook | Colab |
|---|---|
| LangGraph Episodic & Procedural Memory (Tools) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_2_HANDS_ON_Session_2_langgraph_episodic_procedural_tools.ipynb) |
| LangGraph Episodic & Procedural Memory (Tools) — Solution | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_2_HANDS_ON_Session_2_langgraph_episodic_procedural_tools_solution.ipynb) |

#### Session 5 — Security and Governed MCP

**Demos**
| Notebook | Colab |
|---|---|
| A2A + MCP Governed | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DAY_2_DEMO_Session_5_A2A_MCP_Governed.ipynb) |
| Unsafe Agent Scenarios | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DAY_2_DEMO_Session_5_Unsafe_Agent_Scenarios.ipynb) |

#### Other Day 2 Notebooks

**Demos**
| Notebook | Colab |
|---|---|
| arXiv MCP + LangExtract + Pydantic | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DAY_2_DEMO_arxiv_mcp_langextract_pydantic.ipynb) |
| arXiv MCP + LangExtract + Pydantic (Working) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DAY_2_DEMO_arxiv_mcp_langextract_pydantic_working.ipynb) |
| Tavily Crawl → Structured Handoff | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DAY_2_DEMO_tavily_crawl_structured_handoff.ipynb) |

**Hands-on**
| Notebook | Colab |
|---|---|
| LangGraph Episodic & Procedural Memory (Tools) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_2_HANDS_ON_langgraph_episodic_procedural_tools.ipynb) |
| LangGraph Episodic & Procedural Memory (Tools) — Solutions | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_2_HANDS_ON_langgraph_episodic_procedural_tools_SOLUTIONS.ipynb) |
| Planner Thinking (Nebius) — Solutions | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/DAY_2_HANDS_ON_planner_thinking_nebius_SOLUTIONS.ipynb) |

### Additional Notebooks

Notebooks whose filenames are not tied to a specific day or session.

**Demos**
| Notebook | Colab |
|---|---|
| LangGraph Memory Types | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DEMO_langgraph_memory_types.ipynb) |
| Planner Thinking vs Unified Deep Research | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DEMO_langgraph_planner_thinking_vs_unified_deep_research.ipynb) |
| Research Context: Subagents + Supervisor | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/demos/DEMO_research_context_subagents_supervisor.ipynb) |

**Hands-on**
| Notebook | Colab |
|---|---|
| Tree-of-Thought (ToT) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ORM_AI_Agents_Bootcamp/blob/main/hands_on/ch02_ToT.ipynb) |

## Running the Notebooks

All notebooks are designed for **Google Colab**.

1. Click the **Open In Colab** badge for any notebook above
2. Add your API tokens when prompted
3. Run the cells sequentially

### Using OpenRouter

The notebooks can use OpenRouter through LangChain’s `ChatOpenAI` integration by specifying the OpenRouter API endpoint:

```python
from langchain_openai import ChatOpenAI

LLM = ChatOpenAI(
    model=OPENROUTER_MODEL,
    base_url="https://openrouter.ai/api/v1",
    api_key=OPENROUTER_API_KEY,
    temperature=0,
)
```

Use the OpenRouter model identifier shown on the model’s OpenRouter page, for example:

```text
openai/gpt-5.4-nano
```

### Configuring API Keys

Never commit API keys to the repository.

The notebooks support loading configuration from a `.env` file:

```python
from dotenv import load_dotenv
import os

load_dotenv()

OPENROUTER_API_KEY = os.getenv("OPENROUTER_API_KEY")
OPENROUTER_MODEL = os.getenv(
    "OPENROUTER_MODEL",
    "openai/gpt-5.4-nano",
)
```

#### Option 1: Create a `.env` File

In Colab environments that provide terminal access, such as some paid Colab plans, create a `.env` file in the notebook’s working directory:

```bash
cat <<'EOF' > .env
LLM_PROVIDER=openrouter
OPENROUTER_API_KEY=your_openrouter_key_here
OPENROUTER_MODEL=openai/gpt-5.4-nano
EOF
```

Replace `your_openrouter_key_here` with your actual API key.

To use OpenAI directly instead, the file could contain:

```bash
cat <<'EOF' > .env
LLM_PROVIDER=openai
OPENAI_API_KEY=your_openai_key_here
OPENAI_MODEL=gpt-5.4-nano-2026-03-17
EOF
```

#### Option 2: Create the `.env` File from a Notebook Cell

When terminal access is unavailable, create the file from a Colab code cell:

```python
from pathlib import Path

Path(".env").write_text(
    """
LLM_PROVIDER=openrouter
OPENROUTER_API_KEY=your_openrouter_key_here
OPENROUTER_MODEL=openai/gpt-5.4-nano
""".strip()
)
```

Then load it:

```python
from dotenv import load_dotenv

load_dotenv(override=True)
```

#### Option 3: Set Environment Variables Directly

For a temporary Colab session, environment variables can also be set directly in a notebook cell:

```python
%env LLM_PROVIDER=openrouter
%env OPENROUTER_API_KEY=your_openrouter_key_here
%env OPENROUTER_MODEL=openai/gpt-5.4-nano
```

These values exist only for the current Colab runtime and must be entered again after the runtime is restarted.

---

Design deliberately.  
Deploy responsibly.


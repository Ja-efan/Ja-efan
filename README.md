# Jaehwan Yeon · AI Engineer

**English** · [한국어](README.ko.md)

I build AI products, from defining user problems to developing and evaluating agents.

[Portfolio (Korean)](https://jaefan.notion.site/Jaehwan-Yeon-200d2e168cd380abb942c7bf82c704b5) · [jaehwan.contact@gmail.com](mailto:jaehwan.contact@gmail.com)

## Cutback · AI Engineer
Aug 2025–Sep 2026

**Script-based Editing: Initial Development and Pipeline Redesign**  
Built the initial script-based editing feature and later led its redesign based on user interviews. Co-designed the pipeline, coordinated module interfaces, structured input and output data, and implemented and evaluated the retake-grouping module.

**Visual Editing: Building a Video Editing Pipeline with Visual Context**  
Built a pipeline that identifies visually meaningful segments from video keyframes and generates descriptions for editing and search. Extended editing support to selecting and assembling requested scenes in videos without speech.

**Agent Optimization: Reducing Execution Time and Cost**  
Optimized how agents receive context and execute tasks by reusing common inputs and preparing task data in advance. Context caching reduced server-side script-based editing costs by about 30%, while optimizations including prefetch, single-shot prompting, and inference settings cut execution time by about 21%.

**Evaluation: Automated Evaluation for Multiple Valid Outputs**  
Replaced fixed-label matching in video topic segmentation with LLM-based evaluation against the existing guidelines to recognize multiple valid outputs. Automated batch evaluations and recorded results so model and prompt changes could be compared.

**Architecture Wiki: Keeping Team Knowledge in Sync with Code**  
Helped design and then operated the pipeline in which a coding agent proposes wiki updates as PRs when code changes. Fixed PRs overwriting each other and added a daily Slack digest that pings reviewers about wiki PRs left unreviewed for over 24 hours. About 100 auto-generated update PRs were merged in 2.5 months, accounting for roughly 79% of wiki changes.

## Selected Projects

- [Hello Job](https://github.com/Ja-efan/HelloJob) — Company-research agents, a [SWOT MCP tool](https://github.com/Ja-efan/swot-analysis-mcp), and an AI backend for job applications.
- [Shoshoshorts](https://github.com/Ja-efan/shoshoshorts) — Image-generation backend, AWS/GCP infrastructure, and CI/CD.
- [MeetGenius](https://github.com/Ja-efan/MeetGenius) — On-device RAG and meeting summaries on Jetson Orin Nano.

## Technologies

Python · TypeScript · FastAPI · Agent · LangGraph · MCP · RAG · Docker · AWS · GCP

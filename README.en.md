# Soya Open Source Standard

## Made for people who do not code

This is a **Skill**, a package of instructions for an AI assistant. Give the assistant a personal method you may share; it follows the rules to explain the project, check privacy, prepare usable instructions and publish when authorized. Coding knowledge is not required for the first try.

Start with “Try it without installation” below: open an AI chat, copy the complete message, add a small public-safe method and send it. Expect a project explanation, example, privacy checks and next steps. The assistant should ask when facts are missing. Your AI service may charge fees; do not enter company materials, passwords or private information.

A **repository** is the project’s GitHub page. A **PR** is a proposed change awaiting review. A **Release** is a fixed version you can download. Installation is optional for the first try.



**Help AI turn personal methods, experience and tools into understandable, usable, privacy-reviewed GitHub projects with verifiable releases.**

让 AI 把个人方法整理成看得懂、用得上、经过脱敏检查且可维护的开源项目。

[中文](README.md) · Version: 0.3.0 · Initial trial version; consult repository Releases for publication status.

## Try it without installation

Copy this prompt into your AI assistant and attach material you have the right to publish. This is a lightweight entry point; install the full Skill for the detailed workflow.

```text
Apply Soya Open Source Standard to the method or project I provide.
1. Include Soya in the title; explain the core function in one sentence in each language.
2. Write complete Chinese and English introductions: background, scenarios, users, inputs/outputs, costs and limitations.
3. Provide the shortest beginner path: a complete copyable prompt or verified installation and invocation steps.
4. Use Soya for the project author’s default public attribution while preserving required third-party public credits. Exclude private identity, work details, internal data, links, code and credentials. Use synthetic examples. Renaming does not establish publication rights; exclude material with unclear ownership.
5. Include examples, licensing, versions, change history, troubleshooting and practical recovery steps.
6. Use branches and reviewable PRs for later AI changes. A PR-only request does not authorize merging.
7. When I explicitly request publication, complete a public repository, fixed tag, published Release and public-download verification. Creating a repository or pushing is insufficient.
8. Write all public instructions for people who do not code: explain the use and an example first, then where to act, what to click/type, what success looks like and what to do if it fails. Explain terms and put developer details later. After every actual release, review the public content as a newcomer; record questions, fix blocking gaps and recheck before acceptance.
9. Credit reused projects, code, assets, prompts and Skills with the original public author, source link, reused scope, your changes and license. Preserve required copyright and notices; distinguish derivatives from inspiration and resolve unknown sources before publishing.
10. Stay within authorization. Never invent tests, installation commands, links or publication success. Report blockers and the smallest action needed.
Input: [attach material you may publish]
Goal: [prepare only / submit changes / publish on GitHub / deploy an online app]
```

## Background

A method that already works for its creator can become a reusable product. AI can nevertheless stop at documentation or an empty repository and miss installation, work-data privacy, versioning or maintenance. This Skill connects those requirements and demands evidence of the requested outcome.

## Users and scenarios

For independent creators, nontechnical AI users and AI Builders publishing personal methods, prompts, Skills, scripts, extensions or small apps. Also use it for AI-assisted PRs and subsequent releases.

It does not replace company approval, intellectual-property review or professional security auditing. It is not a way to publish internal material after merely renaming it. It grants no GitHub permissions and runs no background automation.

## Synthetic example

Input: “I use three questions to review my reading notes each week and want others to use the method.”

Expected output: a Soya reading-review positioning statement, bilingual introductions, a copyable three-question prompt, synthetic input/output, boundaries, a 0.3.0 version and maintenance guidance. Actual publishing happens only when requested and authorized. Missing access must produce a blocker, not an invented link.

This illustrates expected behavior; it is not an executed case study or testimonial.

## Optional: install the full Skill

You can skip this section and use the copyable message above. The details below are for people installing the complete instruction package or helping someone do so.

Keep the entire directory: SKILL.md is the entry point, agents/openai.yaml supplies UI metadata, and references contains detailed guidance.

Give the directory, or this repository link, to an assistant supporting Skill installation:

```text
Install soya-open-source-standard. Inspect its contents, verify this AI tool's installation mechanism, back up any existing version, install the complete directory and verify discovery in a new session. Preserve my configuration and do not run unnecessary scripts.
```

Offline alternative: open the [version download page](https://github.com/soyoungzsy/soya-open-source-standard/releases), choose a version and click Source code (zip), extract it and place the complete directory containing SKILL.md in the AI tool's supported Skill location. Restart or open a new session. Plain chat clients may not support installation; use the lightweight prompt instead.

After installation:

```text
Use $soya-open-source-standard to prepare and publish this project to my specified GitHub repository, including bilingual documentation, beginner onboarding, privacy review, versioning and public-release verification. Report accurate status if blocked.
```

Success means the assistant follows the seven-stage workflow and reports actual evidence, distinguishing local completion from verified publication. Repeating the rules alone is not installation verification.

## Cost, data and limits

The specification has no additional service fee. Bring your own AI tool and GitHub account; AI usage, automatic checks or website hosting may have separate charges. Work only on authorized projects. Do not provide work secrets, credentials or sensitive personal information. Your AI tool and third-party services apply their own data-retention policies; zero retention is not guaranteed.

No network/publishing scripts or automatic data collection are included. v0.1.0 was actually published and all 11 files matched the reviewed source. Reading its public Chinese and English pages showed that the nontechnical entry needed improvement; this version addresses that finding. Installation in an AI tool and a complete AI-run workflow remain unverified.

## Update, uninstall and recover

Back up the old directory, select a fixed version and replace the complete directory while preserving AI tool settings. Restore the backup and start a new session if it fails. To uninstall, remove only this Skill's directory, not projects or user data. Project code, deployment and data recovery require separate procedures described in the references.

## Troubleshooting and support

If undiscoverable, check directory nesting, SKILL.md and AI tool support, then reopen the session. For publishing failures, verify the target account, access and network; never paste access credentials, which work like passwords, into chat. Report the version, AI tool, what you did and error messages with personal and work information removed. There is no dedicated support channel or promised response time yet. Use Issues (the public question area at the top of this project) for ordinary questions after removing personal and work information. A private way to report security problems has not been verified; do not publish secrets in Issues.

## Version and license

[CHANGELOG](CHANGELOG.md) · [MIT License](LICENSE)

Maintenance stage: initial trial awaiting real-project acceptance. Contributions may improve general rules, synthetic examples and reproducible reports; do not contribute internal materials, secrets or real-user data.


## Original authors and sources

When adapting another project or Skill, explain what its author contributed and what Soya changed. Keep required licenses and notices, including in downloads; the absence of a GitHub fork label does not remove this obligation. See the [source and license checklist](references/attribution-and-licenses.md) and [this specification’s source statement](SOURCES.md).

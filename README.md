# KOTC Full-Length Review

Review KOTC-original MCAT full-length attempts with your connected King of the Curve account. Understand available missed questions and build a focused study plan from your KOTC progress.

## What it does

- Lists your available KOTC full-length attempts and reads a selected attempt's review.
- Explains an available KOTC-original review question without guessing missing content.
- Reads your study snapshot, subject performance, and exam progress when relevant.
- Searches and fetches public KOTC learning resources for concept support.

All tools are read-only. This plugin cannot submit answers, change scores, save notes, delete records, or make purchases. An existing KOTC MCAT account and appropriate access are required for personal review. Empty or unavailable review data is reported honestly.

This is not an official AAMC product. It does not access AAMC Prep Hub, provide an AAMC question bank, or support recalled live exam material.

## Designated reviewer demonstration

When the service enables its exact designated reviewer account, all six private tools return only an explicitly labeled KOTC-original synthetic reviewer demonstration, including study snapshot, subject performance, and exam progress. No production profile, preferences, momentum, progress, real exam history, monthly scores, or cohort records are read for these reviewer tool results. Three original circuit questions simulate two answered responses (one correct and one incorrect) and one unanswered response; 50% accuracy describes only the two answered sample questions. This is not a real completed production attempt, a 230-question full-length exam, an AAMC exam, or cohort analytics. Personal profile, preferences, and momentum values are unavailable/null; total and section scaled scores are null, trend is unknown, and monthly/cohort history is empty. Missing authored explanations, option rationales, and takeaways remain null; any independent teaching inference must be labeled separately. Other accounts retain their normal authorized production paths. Public search and fetch still retrieve published educational resources.

The six sample-only tools are `get_my_study_snapshot`, `get_my_subject_performance`, `get_my_exam_progress`, `list_my_full_length_attempts`, `get_my_full_length_review`, and `explain_my_full_length_question`. The sample is available only when the service separately enables it for its exact designated reviewer identity. Normal KOTC sign-in, OAuth read permissions, Firebase account validation, and verified MCAT membership remain required. Callers cannot choose another identity or enable the sample through tool arguments. Existing sign-in and membership verification does not disclose production progress. The sample creates no production exams, attempts, or analytics records. Unknown sample attempt or question IDs fail without a production fallback.

## Connection and data handling

The only MCP server configured by this bundle is:

`https://kotc-full-length-review-347848146862.us-east1.run.app/mcp`

Public KOTC resources are available without a personal account connection. Private review uses KOTC sign-in and OAuth read permissions. For normal learner accounts, the service reads authorized records through the KOTC/Firebase backend. For its enabled exact designated reviewer, all private tool results use only the synthetic sample described above. Information returned by tools becomes available to the AI host in the conversation. The bundle contains no credentials, local executable, lifecycle hook, package installer, tracking script, or separate data-export destination.

Use the host's sign-in flow; never paste passwords or access tokens into chat. Disconnect the connection in the host when you no longer want to use it. Account or privacy requests can be sent to support@kingofthecurve.org.

## Try these prompts

1. Review my latest KOTC full-length attempt and identify my main study priorities.
2. Help me understand a missed question from my KOTC full-length review.
3. Use my KOTC progress to build a focused review plan for this week.

## Release status

Version 1.0.2 is a prepared submission candidate, not evidence of deployment or directory approval. This package describes the separately prepared sample-only runtime; verify that exact runtime is released before using these reviewer instructions. This packaging task did not deploy server code, upload a bundle, complete a platform connection, run hosted reviewer cases, record a walkthrough, or submit a listing. Check deployment and platform receipts separately. The package contains no invented demo URL. A genuine post-release walkthrough and actual five positive/three negative hosted cases remain required before submission; enter only the verified recording URL in the platform review field.

## Publisher and policies

- Publisher: King of the Curve LLC
- Website: https://kingofthecurve.org
- Documentation: https://kotc-full-length-review-347848146862.us-east1.run.app/about
- Support: https://kotc-full-length-review-347848146862.us-east1.run.app/support
- Privacy: https://kotc-full-length-review-347848146862.us-east1.run.app/privacy
- Terms: https://kotc-full-length-review-347848146862.us-east1.run.app/terms

Recheck the public service links and their data-handling descriptions against the exact deployed release before submission.

## License

This package is proprietary and unlicensed. All rights remain reserved by King of the Curve LLC. No redistribution or modification rights are granted by this package.

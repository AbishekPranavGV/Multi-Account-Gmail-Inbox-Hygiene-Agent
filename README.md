Multi-Account Gmail Inbox Hygiene Agent

    Purpose: Manages up to 10 distinct Gmail accounts simultaneously, auto-archiving or deleting clutter from "Promotions" and "Social" tabs to keep inboxes clean.

    Tech Stack: Python, Gmail API (OAuth2 with token management for multiple accounts), google-auth-oauthlib.

    Key Features:

        Batch Authentication: Handles multi-account credential rotation securely via environment variables or a local encrypted token store.

        Smart Filtering: Targets specific system labels (CATEGORY_PROMOTIONS, CATEGORY_SOCIAL) with bulk archive or trash operations.

        Execution Logs: Outputs a clean CLI or terminal dashboard summarizing how many emails were cleaned per account during each run.

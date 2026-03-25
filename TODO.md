# TODOs for feature/issue-60-dlq-count

## Remaining Steps:
1. [x] Edit src/storage/mod.rs: Add DlqCount to StorageKey, increment in push, decrement in remove, add get_count fn
2. [x] Edit src/lib.rs: Call dlq::remove in retry_dlq, add get_dlq_count query
3. [ ] git add ., git commit -m "Add DlqCount key to track total DLQ entries without scanning (#60)"
4. [ ] git push origin feature/issue-60-dlq-count
5. [ ] Check if gh CLI installed (gh --version), if not install; then gh pr create --title "Add DlqCount key (#60)" --body "Add DlqCount to track total DLQ entries. Increment on push, decrement on remove, expose query." --base develop

Updated after each step.
4. [ ] git push origin feature/issue-60-dlq-count
5. [ ] Check if gh CLI installed (gh --version), if not install; then gh pr create --title "Add DlqCount key (#60)" --body "Add DlqCount to track total DLQ entries. Increment on push, decrement on remove, expose query." --base develop

Updated after each step.

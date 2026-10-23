# bug-fix

```xml
<task>
Goal: fix "{{BUG}}".
Done: the failing case passes, nothing else changes, one-line summary.
Context: {{FILE}}, the error output, steps to reproduce.
</task>
<plan>
1. Reproduce the bug from the steps.
2. Find the line where it goes wrong.
3. Make the smallest change that fixes it.
4. Run the failing case and the cases around it.
5. Summarize: cause, fix, what you tested.
</plan>
<stop>
Cannot reproduce it: ask me for one more detail. Do not guess a fix.
</stop>
```

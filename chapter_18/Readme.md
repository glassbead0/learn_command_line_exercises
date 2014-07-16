English | `code`
--- | ---
Does your log file have any GET requests? | `grep 'GET' *.log`
Can you show me the gem lines from your Gemfile? | `grep gem Gemfile`
Can you print all the lines in text files that have your first and last name in them? | `grep 'Aaron Glasenapp' *.txt`

Do more

Question | answer
--- | ---
Use quotes to find 'new file' and 'old file' and 'This is' | `grep 'new file' *.txt` `grep 'old file' *.txt` `grep 'This is' *.txt`
Take the list of videos you created and use it to find some videos | Assume the videos are listed in videos.txt, and I want to find pinky and the brain: `grep -i 'Pinky*Brain*' videos.txt`

the -i option ignores case

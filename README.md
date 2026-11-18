# SkillBridge-READMEhlyther.md
37
https://github.com/actions/runner-images/issues/14748تخطي إلى المحتوى
w3c
سبيكبيروس
التنقل في المستودع
رمز
مشاكل
37
 ( 37 )
طلبات السحب
2
 ( 2 )
التدقيق الإملائي
مهمة (التبعيات): ترقية express-fileupload من الإصدار 1.5.2 إلى الإصدار 1.6.0 #4296
التعليقات التوضيحية
إشعار واحد
lint
نجح الأسبوع الماضيفي 18 ثانية
0 ثانية
1 ثانية
1 ثانية
10 ثوانٍ
2 ثانية
1 ثانية
0 ثانية
Post job cleanup.
/usr/bin/git version
git version 2.56.0
Temporarily overriding HOME='/home/runner/work/_temp/97c6ad78-763f-455e-8084-cbb77579c279' before making global git config changes
Adding repository directory to the temporary git global config as a safe directory
/usr/bin/git config --global --add safe.directory /home/runner/work/specberus/specberus
Removing SSH command configuration
/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
Removing HTTP extra header
/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
Removing includeIf entries pointing to credentials config files
/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
includeif.gitdir:/home/runner/work/specberus/specberus/.git.path
includeif.gitdir:/home/runner/work/specberus/specberus/.git/worktrees/*.path
includeif.gitdir:/github/workspace/.git.path
includeif.gitdir:/github/workspace/.git/worktrees/*.path
/usr/bin/git config --local --get-all includeif.gitdir:/home/runner/work/specberus/specberus/.git.path
/home/runner/work/_temp/git-credentials-f64955e1-4c0f-40a9-a063-46def156b20e.config
/usr/bin/git config --local --unset includeif.gitdir:/home/runner/work/specberus/specberus/.git.path \/home\/runner\/work\/_temp\/git\-credentials\-f64955e1\-4c0f\-40a9\-a063\-46def156b20e\.config
/usr/bin/git config --local --get-all includeif.gitdir:/home/runner/work/specberus/specberus/.git/worktrees/*.path
/home/runner/work/_temp/git-credentials-f64955e1-4c0f-40a9-a063-46def156b20e.config
/usr/bin/git config --local --unset includeif.gitdir:/home/runner/work/specberus/specberus/.git/worktrees/*.path \/home\/runner\/work\/_temp\/git\-credentials\-f64955e1\-4c0f\-40a9\-a063\-46def156b20e\.config
/usr/bin/git config --local --get-all includeif.gitdir:/github/workspace/.git.path
/github/runner_temp/git-credentials-f64955e1-4c0f-40a9-a063-46def156b20e.config
/usr/bin/git config --local --unset includeif.gitdir:/github/workspace/.git.path \/github\/runner_temp\/git\-credentials\-f64955e1\-4c0f\-40a9\-a063\-46def156b20e\.config
/usr/bin/git config --local --get-all includeif.gitdir:/github/workspace/.git/worktrees/*.path
/github/runner_temp/git-credentials-f64955e1-4c0f-40a9-a063-46def156b20e.config
/usr/bin/git config --local --unset includeif.gitdir:/github/workspace/.git/worktrees/*.path \/github\/runner_temp\/git\-credentials\-f64955e1\-4c0f\-40a9\-a063\-46def156b20e\.config
/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
Removing credentials config '/home/runner/work/_temp/git-credentials-f64955e1-4c0f-40a9-a063-46def156b20e.config'
0 ثانية
Cleaning up orphan processes
remote.origin.urlsafe.directory

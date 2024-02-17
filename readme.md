Удалить все коммиты из гит
git update-ref -d HEAD
git push origin HEAD --force

Откатить 1 коммит назад
git reset --hard HEAD~1

Перейти на коммит
git reset --hard <sha1-commit-id>

Если уже запушил коммит
git push origin HEAD --force


Откатить коммит, но все данные будут в 2х коммитах в гите
git revert
#aSDZAMAgit 初始化
echo “# 我的项目” >> README.md
git 添加 README.md
git commit -m “初始提交”

对于 i 在 {1..10};做
echo “提交$i行” >> README.md
git 添加 README.md
    # 生成随机时间（2025年6月内）
天 = $（（10 + 随机 % 10））
小时=$（（随机 % 24））
min=$（（随机 % 60））
秒=$（（随机 % 60））
export GIT_AUTHOR_DATE=“2025-06-${day}T${hour}：${min}：${sec}”
export GIT_COMMITTER_DATE=“$GIT_AUTHOR_DATE”
git commit -m “提交$i”
    echo "提交 $i 时间: $GIT_AUTHOR_DATE"


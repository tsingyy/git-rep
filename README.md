orphan branch
#���ȿ�¡�ֿ�
$git clone https://github.com/tsingyy/git-rep.git
#����Ŀ¼��Ȼ���½���֧
$cd git-rep
$git checkout --orphan newbranch
#ɾ����Ŀ¼���������ļ���Ȼ���½�README.md��Ȼ��������������ύ�����زֿ⣬Ȼ�����͵�Զ�ֿ̲�
$git rm -rf .
$echo "orphan branch" > README.md
$git add .
$git commit -m "add file README,md"
$git push origin newbranch
#����������������вֿ��ϴ����¶���֧���¶���֧����˼���Ǹ÷�֧��û���κ����ݣ
#��֮ǰ������������֧û���κι���

111111111111111111111
22222222222222222222
33333333333333333333
44444444444444444444
���͵�Զ�ֿ̲���ٴ��޸�
add branch dev
add branch branch1
make conflict

4.��ʼ��������ǰĿ¼���git�ֿ�
git init

5.���һ��txt�ļ�������ӵ��ֿ��ݴ���
git add readme.txt

6.�ύ
git commit -m "commit message"

7.�鿴�Ƿ����ļ�û���ύ
git status��Ȼ���޸�readme�ļ���

8.�鿴�޸���ʲô
git diff readme.txt

9.�鿴�ύlog��־
git log/git log --pretty=oneline

10.�汾����
git reset --hard HEAD^���ص���һ���汾��/git reset --hard HEAD^^���ص��������汾��/git reser --hard HEAD~100���ص���100���汾��

11.���˺�鿴��ǰ�ļ�������
cat readme.txt

12.�����ص�����ǰ�����°汾
��ȡ���е�log��־   git reflog
�ص����� git reset --hard xxxxxx

13.�����޸�readme��δ�ύ֮ǰ�����д���
cat readme.txt �����д���
�����ֶ��޸ĺ�add+commit
Ҳ����git reset --HEAD^
Ҳ����git checkout -- readme.txt (--�����пո�)


14.ɾ���ļ�
rm a.txt

15.�ָ���ɾ�����ļ�
git checkout -- a.txt(--�����пո�)


16.���͵�Զ�ֿ̲�
git remote add origin https:.........git
git push -u origin master

17.�����޸ĺ����͵�Զ�ֿ̲�
git push origin master


18.�������л�����֧dev
git checkout -b dev
������֧��git branch dev
�л���֧��git checkout dev

19.�鿴��֧
git branch

20.�л�������֧master��Ȼ�󽫷�֧�ϲ�
git checkout master, git merge dev

21ɾ����֧
git branch -d dev


22.�����ͻ
�½����л����·�֧branch1��git checkout -b branch1

�鿴readme�����ݣ�cat readme.txt

�޸�readmeȻ��鿴
��ӣ�git add readme.txt + commit

�л�����֧master��git checkout master

��master���޸�����
��master��git add readme + conmmit

��master�ϲ���branch1�ϣ�git master merge branch1


�ֶ��޸����ݣ�Ȼ��add+ commit




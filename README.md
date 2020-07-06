# LaTeX ������ ��� ������� INJOIT
����������� �������� LaTeX ������ ������ ��� ������� International Journal of Open Information Technologies ([INJOIT](http://injoit.ru/)).
������ ������� �� ������� [IEEEtran LaTeX](http://www.michaelshell.org/tex/ieeetran/).

��� ����� �������� `cookiecutter`-������ ([more details](https://cookiecutter.readthedocs.io/en/latest/)) LaTeX-�������.

__��� ������������ ������__:
1. ���������� `python` � `git`;
2. ���������� ���������� `cookiecutter`, �������� � ��������� ������ ��������� �������:
   ```bash
   pip install cookiecutter
   ```
4. ��� ������������� ������ ������� ��������� � ��������� ������:
   ```bash
   cookiecutter https://github.com/gf2crypto/injoit-template.git -c cc
   ```
5. ���������:
     - **project_name**, ��� ������� (�������������� ������ ��������);
     - **create_gitignore**, ��������� �� ������� `.gitignore` ���� ��� ������������� ������� �������� ������ `git`: 'yes' ��� 'no'.
6. ��� ���������� ��������� ����� ������������ ������� `make` (`make.bat` ��� `Windows`).
7. ��������� `make help` (`make.bat help` ��� `Windows`), ����� ������� ������ ��������� ����� ����������. ������������� �������� �������� �� ����� `watch`, ������� ������������ ����������� ���������� ������� � ��������� ������ ��������� � `pdf` ����������� � ������ ��������� �������. __�������� ��������__, ��� `make`-����� ���������� `latexmk` ��� ���������� ���������. �������� ������� ���������� ���� �����. ������������� ������������� __������__ ������ `LaTeX`, ����� ���������� ����� �� ������� � ����������� �������!
6. ����� �������� ���������� �������. __��������__! ������ �� ������������ ���������� � ������� `pdflatex`! ����������� `xelatex` (�� ������ � ������ ����������� LaTeX �������������).
��� ���������� ������� ������ ��������� ��������� ������������������ ������:
```bash
xelatex project_name
biber project_name
xelatex project_name
biber project_name
xelatex project_name
```

## ������������� �������
 * ��������� �������� � ����� `config.tex`.
 * ��������� ������� � ����� `images` � ��� ����� ������������� "��������������" ��������
 * ������������ ��������� � ���� `%_ru.bib`.
 * �� ����������� ������� ����� ������������ ������������ �� ���������� ����� ��� ����� ������������ ��������� �������� ��� ���������, � ������������� ������� ����������, � ����� ����������� �� ����������. ���������� ������ ������������ ��������� � ���� `%_en.bib`. �� �������� ������������� ����� ����������������� ������� � ���������� ������, ����� �� ���� ���������� (��. ������ � ����� `%_en.bib`).
 * �� �������� � ��������� �������� ������� �������� ������ ������ � ����� ������ �������� (��. ����� ����� `config.tex`)

# LaTeX ������ ��� ������� INJOIT
����������� �������� LaTeX ������ ������ ��� ������� International Journal of Open Information Technologies ([INJOIT](http://injoit.ru/)).
������ ������� �� ������� [IEEEtran LaTeX](http://www.michaelshell.org/tex/ieeetran/).

����� ������� `cookiecutter`-������ ([more details](https://cookiecutter.readthedocs.io/en/latest/)) LaTeX-�������.
��� ��������� � ����� `cc` ([���������](https://github.com/gf2crypto/injoit-template/tree/cc)).

## ����������
**��������!** ������ �� ������������ ���������� � ������� `pdflatex`! ����������� `xelatex` (�� ������ � ������ ����������� LaTeX ������������� �, ������ �����, ��� ���������� � ���).

������ ����������:
```bash
xelatex injoit-rus
biber injoit-rus
xelatex injoit-rus
biber injoit-rus
xelatex injoit-rus
``` 

������������� ��� ���������� ������������ ������� `make` (`make.bat` ��� Windows). ������ ������ �����, ��� ��� ������� ���������� `latexmk`. ��������, ����� ����� ���������� ���� �����.

__������������� ������������� ������ ������ `LaTeX`, ����� ���������� ����� �� ������� � ����������� �������!__


## ������������� �������
 * ��������� �������� � ����� `config.tex`.
 * ��������� ������� � ����� `images` � ��� ����� ������������� "��������������" ��������
 * ������������ ��������� � ���� `%_ru.bib`.
 * �� ����������� ������� ����� ������������ ������������ �� ���������� ����� ��� ����� ������������ ��������� �������� ��� ���������, � ������������� ����������� �� ����������. ���������� ������ ������������ ��������� � ���� `%_en.bib`. �� �������� ������������� ����� ����������������� ������� � ���������� ������, ����� �� ���� ���������� (��. ������ � ����� `%_en.bib`).
 * �� �������� � ��������� �������� ������� �������� ������ ������ � ����� ������ �������� (��. ����� ����� `config.tex`)

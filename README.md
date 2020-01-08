# Резюме в формате латеха.

## Для редактирования в среде Ubuntu + VSCode:

1. &nbsp; Установить расширение LaTeX Workshop

2. &nbsp; Установить LaTeX, сборщик PDF, поддержку кириллицы, автоформаттер и perl-либы к нему:

   `sudo apt install texlive latexmk texlive-lang-cyrillic texlive-extra-utils`

   `cpan Log::Log4perl`

   `cpan Log::Dispatch::File`

3. &nbsp; Перезапустить VSCode и начать писать \*.tex-файлы
4. &nbsp; ...
5. &nbsp; Profit!

## Альтернативы

Есть еще популярный онлайн редактор overleaf.com (бывший writelatex.com), но для синхронизации с гитом нужна платная подписка (заплатить, стать волонтером или насобирать рефералов).

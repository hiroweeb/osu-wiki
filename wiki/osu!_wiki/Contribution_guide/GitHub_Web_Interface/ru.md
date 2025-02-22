# Веб-интерфейс GitHub

*Эта статья является продолжением основного руководства.* Если вы собираетесь редактировать несколько статей или файлов, воспользуйтесь [GitHub Desktop](/wiki/osu!_wiki/Contribution_guide/GitHub_Desktop).

## Редактирование

1. Откройте форк `osu-wiki`.

2. Перейдите к файлу, который вы хотите отредактировать. Файлы сгруппированы следующим образом: название директории означает название статьи, к которой относится содержимое, а внутри расположены переводы на разные языки, имеющие расширение `.md`.

3. Кликните по нужному файлу.

4. Кликните по иконке с карандашом.

   ![](img/online-editing.jpg "После нажатия на карандаш появится окно редактора")

5. При внесении правок следуйте [критериям оформления статей](/wiki/Article_styling_criteria), насколько это возможно.

6. [Сделайте коммит](#коммит), чтобы сохранить изменения.

### Перемещение файлов

*Внимание: через веб-интерфейс GitHub **не рекомендуется** перемещать несколько файлов, потому что на каждое перемещение будет создан отдельный коммит. Это, в свою очередь, делает историю изменений [менее понятной и наглядной](/wiki/osu!_wiki/Contribution_guide/Best_practices#making-edits).*

1. Найдите файл, который вы хотите переместить, и откройте его.

2. Кликните по иконке с карандашом.

3. Над текстовым редактором появится поле, куда вписан текущий путь к файлу.

   ![](img/online-move.jpg)

4. Измените путь на желаемый. Чтобы переместиться на уровень выше, сотрите текущее название целиком. Чтобы переместиться на уровень ниже, введите `/`.

5. Когда вы полностью ввели путь к файлу, введите его имя, не забыв про расширение, `.md`.

6. [Сделайте коммит](#коммит), чтобы сохранить изменения.

### Создание файлов

1. Откройте форк `osu-wiki`.
2. Перейдите в директорию, где вы хотите создать файл.
3. Нажмите на кнопку `Create new file`.
4. Введите местоположение и/или имя файла статьи, которую вы хотите создать. Путь к файлу должен иметь следующий вид: `wiki/`, затем название статьи, затем [код языка](/wiki/Article_styling_criteria/Formatting#локали) (`ru` для русского), затем `.md`. Пример: `wiki/Legal/Copyright/ru.md`.
5. [Сделайте коммит](#коммит), чтобы сохранить изменения.

### Выгрузка файлов

1. Откройте форк `osu-wiki`.
2. Перейдите в директорию, куда вы хотите выгрузить файл.
3. Нажмите на кнопку `Upload files`.
4. Выберите файлы, которые вы хотите выгрузить.
5. [Сделайте коммит](#коммит), чтобы сохранить изменения.

*Примечание: вы также можете выгружать директории целиком.* Это полезно, если на вашем компьютере уже есть новая статья, состоящая из нескольких файлов.

### Удаление файлов

*Внимание: через веб-интерфейс GitHub **не рекомендуется** удалять несколько файлов, потому что на каждое удаление будет создан отдельный коммит. Это, в свою очередь, делает историю изменений [менее понятной и наглядной](/wiki/osu!_wiki/Contribution_guide/Best_practices#making-edits).*

1. Откройте форк `osu-wiki`.
2. Найдите файл, который вы хотите удалить, и откройте его.
3. Кликните по иконке с мусорным ведром.
4. [Сделайте коммит](#коммит), чтобы сохранить изменения.

## Коммит

Коммитом в терминологии git и GitHub называется набор связанных изменений. Делая коммит, вы сохраняете свои наработки.

1. Когда вы закончили вносить изменения, пролистайте вниз страницы до подобной формы:

   ![](img/online-commit-changes-empty.jpg "Верхнее поле — самое важное")

2. **Всегда заполняйте краткое описание изменений!** Оно должно быть написано на английском языке и умещаться в 72 символа.

3. При желании можно составить более подробное описание в следующем поле (например, так):

   ![](img/online-commit-changes-filled.jpg "Пример описания")

4. Если вы после этого изменения собираетесь сделать ещё несколько, относящихся к этой же статье, выберите пункт `Create a new branch for this commit and start a pull request`, чтобы изменения можно было объединять в одну цепочку, и переходите к шагу 5. Если это всё, что вы хотите сделать, выберите пункт `Commit directory to the {xxxxxx} branch` и переходите к шагу 6.

5. Придумайте название для новой ветки. Рекомендуется выбирать название, исходя из сути изменений; например, ветку, где вы переводите критерии ранкинга, можно назвать `ru-ranking-criteria-1`.

6. Нажмите на зелёную кнопку. В зависимости от выбранного варианта, там будет написано либо `Propose file change`, либо `Commit changes`.

7. После этого ваши изменения будут сохранены, и перед вами откроется окно для создания пулл-реквеста. **Ничего в нём не делайте — оно относится к вашей копии репозитория.**

   ![](img/pull-request-pippi-osu--osu-wiki.jpg "Это окно можно закрыть")

8. Переходите к [публикации изменений](/wiki/osu!_wiki/Contribution_guide#публикация-изменений) в оригинальный репозиторий.

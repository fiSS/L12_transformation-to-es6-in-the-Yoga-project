# L12_transformation-to-es6-in-the-Yoga-project
приведение проекта YOGA в соответствие  с ES6:
class Options, добавил свойства данному классу height, width, bg, fontSize, textAlign.
constructor(height, width, bg, fontSize, textAlign).

При помощи метода document.createElement('div') создал новый DOM-элемент div на странице.
Чтобы DOM узел был показан на страницен, вставил его в документ Document.body.appendChild(elem).
При помощи cssText изменил свой стиль из переданных параметров.

Создал новый объект через класс const item, вызвал его метод и получил елемент на странице item.createDiv().

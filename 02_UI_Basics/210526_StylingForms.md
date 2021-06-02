# Review of forms

* [Forms Basics](Forms-Inputs.pdf)

## Validation
- [ ] `required` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/required)
- [ ] `minlength` & `maxlength` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/minlength)
- [ ] `pattern` = regular expression [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/pattern)
- [ ] `title` attribute to describe the pattern (tooltip) [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/title)

- [ ] [Email validation](https://en.wikipedia.org/wiki/Email_address#Syntax)

## Other attributes
- [ ] `autofocus` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)
- [ ] `disabled` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/disabled)
- [ ] `readonly` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/readonly)

### Pseudo-classes
- [ ] `:valid` [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/:valid)
- [ ] `:invalid` [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/:invalid)
- [ ] `:required` [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/:required)
- [ ] `:autofill` [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/:autofill)
   * [Styling autofilled elements](https://css-tricks.com/snippets/css/change-autocomplete-styles-webkit-browsers/)
- [ ] `:checked` [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/:checked)
- [ ] `:disabled` [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/:disabled)
- [ ] `:placeholder` [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/::placeholder)
- [ ] `:placeholder-shown` [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/:placeholder-shown)
- [ ] `:focus` [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus)
- [ ] *`outline`* [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/outline)
- [ ] [more...](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes#the_input_pseudo-classes)

## All the Inputs
* [Form Inputs](Forms.pdf)

- [ ] `<input type="search">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/search)
   * `name="q"`
   * × to delete contents
   * May show previous search terms

- [ ] `<input type="button">`
   * No label required
- [ ] `<input type="checkbox">`
   * Multiple buttons in group with same `name`
   * Style as toggle switch
- [ ] `<input type="color">`
   * Different in different browsers (Chrome, Firefox, Epiphany, ...)

- [ ] `<input type="date">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/date)
   * `YYYY-MM-DD` format for `value`, `min` and `max`
   * `step` starts from `min` date, if present
   * Use `pattern` for older browsers with text-only input
   * Show validation with `::after`

- [ ] `<input type="datetime-local">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/datetime-local)
   * Limited support

- [ ] `<input type="file">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/file)
   * `accept`
     * `audio/*`, `audio/mp3`
     * `video/*`
     * `image/*`
     * file type specifiers
   * `capture`: visitor can use microphone or camera
   * `multiple`
   * Need server-side treatment to store uploaded file
   * Cannot

- [ ] `<input type="hidden">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/hidden)
   * Invisible to user
   * Example: id of database record being edited

- [ ] `<input type="image">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/image)
   * Provides `x`, `y` coordinates of click
- [ ] `<input type="month">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/month)
- [ ] `<input type="number">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/number)
- [ ] `<input type="password">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/password)
   * Set `type` to `text` to show content
- [ ] `<input type="radio">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/radio)
   * Multiple buttons in group with same `name`
   * `checked`
   * Style as toggle switch
- [ ] `<input type="range">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/range)
- [ ] `<input type="reset">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/reset)
- [ ] `<input type="submit">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/submit)
- [ ] `<input type="tel">`
- [ ] `<input type="text">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/text)
- [ ] `<input type="time">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/time)
- [ ] `<input type="url">` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/url)
- [ ] `<input type="week">`[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/week)
---
- [ ] `<textarea>` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea)
- [ ] `<select>` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select)
- [ ] `<optgroup>`[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/optgroup)
- [ ] `datalist` [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist)



## Styling Tricks

- [ ] `<fieldset>` [w3.org](https://www.w3.org/TR/2016/REC-html51-20161101/rendering.html#the-fieldset-and-legend-elements)
- [ ] `<legend>`
   *  `direction: rtl` must be set on parent `<fieldset>`

- [ ] [CSS-only toggle switch](https://dev.to/dcodeyt/creating-a-css-only-toggle-switch-5cg3)

- [ ] Custom styling radio buttons

## Exercises

* [Data Form](https://classroom.github.com/a/eT2DKHK2)
  ![Data Form](data_img/data_form.png)
* [Styling Forms](https://classroom.github.com/a/Rg7m6gzH)
  ![Styling Forms](data_img/styling_forms.png)
* [Transparent Login](https://classroom.github.com/a/DmimjUc5)
  ![Transparent Login](data_img/transparent_login.png)

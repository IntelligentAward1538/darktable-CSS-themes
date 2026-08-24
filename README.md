# 'Oasis' CSS theme for [darktable](https://www.darktable.org/) 5.6+

## News:
- Improved hovering over history stack items.
- Active modules display a gradient.

## Screenshots last release : 260823-Base

<img width="2560" height="1390" alt="Lighttable" src="https://github.com/user-attachments/assets/25a2b4aa-9e09-40a4-bd89-dd406ba19360" />
<img width="2560" height="1390" alt="Darkroom" src="https://github.com/user-attachments/assets/4a940d39-593f-4e9d-8100-c30ba405495d" />
<img width="446" height="821" alt="mask editor" src="https://github.com/user-attachments/assets/3f776a0c-6267-4f88-9cba-a168d2d8ea46" />

## <b>Motivation:</b>

"darktable.css" (67Kb) is the only complete theme included in the distribution.The remaining options simply import this first one and make some variations, but without significant changes.

I understand the motivation behind official themes, but over the years, visual acuity declines and the field of vision narrows.

This means that the interface and color palettes of the themes included in the darktable distribution cause me considerable eye strain and unwanted interactions. They also lengthen editing time and require more troubleshooting.

Therefore, the objectives are:
<ul>
<li>Reduce eye strain.</li>
<li>Enhance the placement of elements by grouping them into tabs and using specific colors based on function.</li>
<li>Improve mouse interactions.</li>
<li>Use a single, unified CSS file.</li>
</ul>

## <b>Installation:</b>

The CSS file must be in the folder where all your darktable themes are saved.

Open darktable and select the new theme in the general settings.

Uncheck the option to use any text you have as additional CSS. Do not click "Save CSS and apply" (this will re-enable it).

When choosing a new theme, it is recommended to restart darktable so that all changes are displayed correctly from that point on.

## <b>Compatibility:</b>

I use some new classes that were created in version 5.6. Earlier versions won't recognize them and won't work properly.

On my 15-year-old PC, running Windows 10 and darktable 5.6, it works correctly[*]. I don't know about other systems. Tell me about your experience using it.

If your computer has other fonts, you might need to edit the "font-family" lines.

[*] In the distribution's themes, some tabs can be confusing when they light up even after the mouse has moved away. This doesn't happen here.




# es-plantuml
Event storming PlantUML diagram template and VS Code snippets

## Warning - Incomplete

I started working on this event-storming plant uml template inspired by [C4-PlantUML](https://github.com/adrianvlupu/C4-PlantUML) but found it impractical to use due to layout limitations in PlantUML.  Event storming relies a great deal on being able to position elements relative to other elements. PlantUML supports this in theory, but in practice I found the layout results to be unpredicable. See [Known Issues] for more details.

## Sample Diagram

Source: [samples/EventModel.puml](samples/EventModel.puml)

![Feature_Explorer_Event_Model](https://www.plantuml.com/plantuml/png/0/hLdfK-Eu4l_klw8dErK35B0GZZagazgGWw4saAaGbffw-oebR2LnOLjUIHacRtV-zzUIx5W-GhA1V818wkFNxRxa_2OauN8U1j2ZHCuv7NT_n07Zb8-xtsaanzVCeu7p3lGARYNZeHzD7TnfCwGJ-EMNjH_7UJCDs0C9u6rhE1pSZtk3cz6uFUWFXl0PQh_Kpq_g9nzg5jd5uEwcqnf-MqLP9hmO33lTuRD2-ztBxasdABAdFxKIsUXgrEyMYO_qfqnyqMh_VZbKM39YoKaaOiBHSNdJya1pP0K_FMTDUt3JxWvlrffp--rsrBrUIzRzeui4wwXQbvV3xcLhjDunmswhCxuUTBhzjKBRW-lhrWOFvkkWVzN-jegix9cBIukispixEJig-oL7r3iwht-ibxoIf-bz_92pDFD9WQvxSN9HxP4SuMcxrSiXI_sHepewQNtidPQzaICwVt_IkdYFli2ql9MBGANgPWagMGoImGEJaeNW-PowqcUHC_Cz2gxFtO22MOGqVA2O-7eX9EMKoKLC7KSy-X76CGdXse_Q0H7YtlVa38wFZgmpCICUUq9WC261eDP9XAL6q1ZfhKrCZiVIfaSdP1x84VqXMu4_ZK9LcrpyGxaDuucJs42e8mHqX52vDgN10WILKc6GCme1dTB8WmbJGbHHKuvuclcI0Y9ao8U5CHAQze5n3urFZW_KVtS6ljeW4gxWYKJoyF3G0j7NqdieN1VCYYfK8hxGIX9okroKAOdxEELi7dbvuSLoP36k5cuHkUhfmTyEuETs-OYL4RV-_oWSrvsVDdcBS_QKa2UIhVgbjoq755l0yhnIjWf4V6W1RJIKfN6pcIZA95eLL9_O9jfdg-G-A0SIlgWGNTM8IZggcv15fbAHWaV4Z7fv5DhHZORB8fVog0f0kSnNwI-gBSP5iIHMeX0BJEUm2aIfXso3eL1mAo5GDMPK8IYsfsq0v8jvfNuodN8w9P9MOQXgVjlWA3UCIYoS4YzKurSLbihskWsOYgwq8aJ3a4HUTOWM-_Ts8PhlUfKeOXRuRcMYbeQ3RJ0KUgg2WEM_JnPiBZUTT2VpIBTEwBU-3Uv6u_khqPUngSixkwMkcJIVfEzoVpgJpZyDtOO-hPf4ctjxflplxJL-rQHD-0UvIbdUX5HIkOeqavgJbr38qKn0gG8qJRN8i-SpBECkPczJvtcUjvmL6NzLvZMNkPgNKn7GcQ3Aj6cgJ0ETQaL_vaFIzcSnv9j9WkGb508g4r0ArwO9ROiT7x293kSD_ad3gYB2HeEluyxW_WR3QzKOjqP2lziRZOTNbrz6Exk0CJcHIegEnfL2tc5owRxfqurlWVFehpcJ58Uj582MGJ7_S7Zx8NVUai0dOX_U1kI11hlEiaj3xVDdi_bdr10uA7mwhZVpp8rVrNwp1hcE3aI0aGeb0oxLGF42y9e_mPp3gWyKa7HaoK106KOte6g2VG6GjidbWllmFqxKBlzSg-qwPgIplFXdb1pNB7JsA58CchBQMrq2NaFhSlHOhrI_YNWDdUciiLvbAwqqhw7M7Z7MgnvYQTBlO5wk6l8ZnNhTRLFHLcl6hyILp81uuqzWnwpX3Lv6QrX9DWBMIAH04-mn0_7X_H3-HU0cdDemVxBUlg-wuhx6CrsE9QNS7jA0gEzYviVRvtTVQH_l61IMj_KwyRRpAR5WO_k7MgQsuNW_CQPk-o6j_5fZGcXjfonvUBiRATvvE-4iH2MIfHgr5eEfTBOFjOE3fWgfZQnIWzs_rz0uEAXjXdvyGx4tFZ2-XHdDJNKe8rwWgB6nCPqjhF3OKrGsPPK297ur7QkKt6sXOHvlRCDT_4hoLodeRo5VJMeRMz17ubVJiKh9S0iDUixSs8oXeduzBSlx7NoXGKovU4cLNkHo2Mkc-Wu7_y5RdqUZ_te7QdkjbKhEtNDovflB6JudXsykf_-SdA12ZlCkVuq8Z9Enqyz9eD_0qb2euvWpR-vIl7zn2cm213UnLQhaJvaEu46n1e91I8MW0kOnC3cZ7EJCZwO20l-HGeIm8Gw8gyTfvrt5vKOzxaIekYff9RvvjPkyLDu7rEABw9q4d9OKKax_ccFByrIab2vSbPTyH_eIhm5xU_bVpQ3ZaoaduTwUunJkFQYeJRWtMiGK9v5QAmX0hK5lODlxsqb7_6G-LqJfs8yXdKpYPepMPsO7Zyoyh8TTTP0Cq7YGJRNBaTGGB9VW8eQQsant111kNek3ljg8myD3dNRfbChJRng4sWUzHA9qd4m6jSG2_HrFas7CJ5BwpEpWqK_7qOyskTMg6B7SvOnc1YYe5oe27endmJMkLO_NymM6nG8tSPx3dGXTWy1GqCJdGXuwHHdAo8p9Zq2_Hj9HY4ZWaSOIC35OH37o8ee2Mieb68p2H27-5_CuPWBPrNqSVIQJ7n1I6ymgX_LGtVaLlrCA4FEx0_fbeB_KTjKBC7F_J5vnQKUAtULhUEDidGwQ1tc_gWNebNggQfooQLs2uHIan6szigbpnDznzlCm8bBoFv9rWU5d7kOoa5ASMH1IxhiaCt2501syIojDREi3RPkNyeDPsbPQjCQqm29VxbYMMWofSHd3SYS32agFgPLvM_SX_uWIic4rMM8XHdqXw4q8w50rkLSEKuvfpl7IPC9rWdSgmKAg2fd0S4Nbu8IBj026nELC2r75ReRT3sjK6igM1X4hLs8OCvWG3YGc_Bb85IIC0vgiq3ctUWt9XWdSf2RXhQE6ERHqORADTv2QV6BBxMLy5kcN1oivJjJ1ZDECnwfwAzIVudh2vhouVwRs_Uyb-dDS2_z7SVkzsbPbjtZm0TTggfTbk2NLovEISikEelKc1fLvxl5k6fGTxJwtlfkjaSyzoQ9HCT3Zx5mz7bgt12hwKuiUr_IqT6ufH7FSirKC7UrfUcQjqKXwRgtHi_IzjKQNqW-h06NwIfcJ2qddtfSpd382BEHuHYUO9kgdMwn-CANg9s2JfljP7nJxZieTtKD5CgXm270KWISSGcZomwygwM7IJ5JIg9Ql6e7qiPqp3rDenkRJcPKxl-6tUHZy7m00 "Feature_Explorer_Event_Model")

## Known Issues

There are some significant issues with this template that have made me abandon it for now. I might pick it up again sometime in the future if I can figure out some reasonable ways to solve these.

### Layout is difficult 

Unfortunately, layout options in PlantUML produce rather inconsistent results - especially when dealing with groups of items. It seems to be impossible to consistently ensure that groups of items are positioned the way you want relative to other groups of items.

In an ideal world, the layout engine would:
* default to displaying each card from left to right in the order that they are listed in the file
* if two of the same type of card are listed in a row, they should automatically stack vertically
* allow you to place cards in groups called bounded contexts
* allow you to place cards in groups called aggregates - which can be placed inside of bounded contexts, but not
inside of other aggregates
* allow you to connect individual cards in bounded contexts to cards in other bounded contexts
* allow you to connect individual cards in aggregates with cards in other aggregates
* allow you to connect aggregates to each other
* allow you to connect bounded contexts to each other
* when items are connected, the groups (bounded contexts and/or aggregates) containing those items can move relative to other groups, but the items within the groups should not move

This might be possible by creating a new layout engine for graphviz and offering that layout option in plantuml... or maybe creating a new mermaid diagram type?... but that's a lot more work than I was planning...


### No auto-wrap for box descriptions

PlantUML has an option called WrapWidth that I was hoping to use, but it doesn't apply to the description lines in the cards I've created. Under the hood, I'm using classes for cards. The wrapwidth option would work if I used rectangles instead, but then I'd lose some other important features that I get with classes but not with rectangles.

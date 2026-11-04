# Pangantucan Bukidnon Community College (PBCC) Website

A draft one-page website for PBCC, based on the MalahSCI site. It uses plain HTML, CSS and JavaScript, so there's no build step. Open `index.html` in a browser to view it.

**This is a draft.** The school hasn't reviewed it. Most content comes from [PBCC's official Facebook page](https://www.facebook.com/pangbukcc/), whose newest posts found were from 2024.

## Before it goes live

**Get the school's permission**

The logo, photos and campus rendering belong to PBCC, and the photos show identifiable students and staff.

**Confirm with the school**
- The address. "Poblacion" comes from a 2017 Asian Development Bank document.
- The phone number, which comes from a [third-party TESDA listing](https://tesdatrainingcourses.com/pangantucan-bukidnon-community-college.html)
- That the four degree programs are current, and whether the TESDA courses on that listing are still offered
- That 2014, the year on the seal, is the year PBCC was established
- That the dress code from the July 2023 notice still applies
- The program descriptions, card text, and enrollment steps, which were written for this draft
- That the campus rendering looks like the real campus

**Fill in the placeholders**

Replace everything highlighted in yellow. In `index.html`, search for `class="ph"`.

**Update the news**

The news cards are from 2024. Replace them with newer stories if the school has any.

**Consider replacing the stock photos**

Three program cards use Unsplash stock photos, which don't show PBCC. If the school has real photos of those programs, save them under the same filenames in `images/programs/`, then update each image's `alt` text in `index.html`.

## Where the images came from

These are from PBCC's Facebook page, resized for the web.

| File | Source |
| --- | --- |
| `logo.jpg`, `favicon.png` | Profile picture |
| `cover.jpg` | Campus rendering (Oct 2022 cover photo), cropped to remove a green swoosh, with contrast and color increased. Replace it if you get a real photo of the building. |
| `photo1.jpg`, `photo3.jpg` to `photo6.jpg`, `programs/criminology.jpg` | ROTC opening ceremony (post dated Sep 2024) |
| `photo2.jpg` | Independence Day flag raising (June 2024) |

These are stock photos from [Unsplash](https://unsplash.com), free to use under the Unsplash License. Credit isn't required.

| File | Photo |
| --- | --- |
| `programs/beced.jpg` | [Teacher and student in classroom](https://unsplash.com/photos/teacher-and-student-in-classroom-6c86TCPmNRQ) by Ronald Felton |
| `programs/agriculture.jpg` | [Person farming on rice field](https://unsplash.com/photos/person-farming-on-rice-field-a7n65pmnJ4Q) by Sandy Zebua |
| `programs/entrepreneurship.jpg` | [Man standing outside a store](https://unsplash.com/photos/a-man-standing-outside-of-a-store-with-his-arms-crossed-r0kv1S72CPw) by Ali Mkumbwa |

## Remove the draft markers

- The `noindex` line in the `<head>` of `index.html`
- The "Draft: some details unconfirmed" badge at the start of the hero section in `index.html`


<div align="center">
  
  <img src="https://github.com/user-attachments/assets/f9c2cf01-a36c-4806-99da-35e57dd380d9" width="120" height="120" style="border-radius: 24px; box-shadow: 0px 4px 10px rgba(0,0,0,0.15);" alt="Hack Date App Icon" />

  # Hack Date

  ###  Light, fast, and dynamic. Web-wrapper built for Android.

  [![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com)
  [![HTML5](https://img.shields.io/badge/Language-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
  [![Architecture](https://img.shields.io/badge/Type-Web__Wrapper-blueviolet?style=for-the-badge)](https://developer.android.com/reference/android/webkit/WebView)
  [![License](https://img.shields.io/badge/License-Apache_2.0-blue?style=for-the-badge)](LICENSE)

  ---

 <p align="center">
  <a href="#-features">Features</a> •
  <a href="https://github.com/Sadrita404/HACK-DATE/releases/tag/V1">Installation</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="https://github.com/Sadrita404/HACK-DATE/blob/main/LICENSE">License</a>
</p>

</div>

---

<div align="center">

| Hack Date App Demo |
| :---: |
| <video src="https://github.com/user-attachments/assets/59b748dd-6175-437b-978b-fba7c2543db8" width="750" controls muted></video> |

</div>

---

|Title | STL VIEWER|
| :-- | :-- |
|Author | Sadrita Neogi|
| APP APK FILE | [APK FILE](https://github.com/Sadrita404/HACK-DATE/releases/tag/V1)|
| Official Website | [LINK](https://hack-date-official.vercel.app/)

---
## What is Hack Date ?

Hack Date is an Android Event Calendar App for HC and it uses Hack Clubs event [api](https://events.hackclub.com/data/) to fetch all the events and show it in the app and we can also add this events to Google Calendar

---
 |Tech Stack|
  |:--|
  | HTML |


---
## App Wire Frame 

<img width="1051" height="589" alt="Hack Date Wire Frame" src="https://github.com/user-attachments/assets/7fc09d12-1881-4a97-85da-70a2d55480e5" />

Made By - Sadrita in [Excalidraw](https://excalidraw.com/)

---

<div id="-features">

##  Features

*  You can saw Hack Club event ever hosted.
* You can see upcoming events and there timelines.
* You can add events directly to your Google Calendar.

</div>

---
## API Setup 

### For Detailed Note Read Hack Club Api [Doc](https://events.hackclub.com/data/)

A simple JSON API to events on this site.

### Filtering

####  You can filter events by tag via the $${\color{darkorchid}\text{?tags=}}$$ query parameter. Multiple tags are comma-separated.

- [`/api/events/upcoming?tags=stardance`](https://events.hackclub.com/api/events/upcoming/?tags=stardance)
- [`/api/events/all?tags=ama,workshop`](https://events.hackclub.com/api/events/all/?tags=ama%2Cworkshop)

### Endpoints

- [`/api/events/upcoming`](https://events.hackclub.com/api/events/upcoming/) – **all upcoming events**
- [`/api/events/upcoming-monthly`](https://events.hackclub.com/api/events/upcoming-monthly/) – **all upcoming, grouped by month**
- [`/api/events/all`](https://events.hackclub.com/api/events/all/) – **all events ever**
- [`/api/events/all-monthly`](https://events.hackclub.com/api/events/all-monthly/) – **all events, grouped by month**
- [`/api/amas`](https://events.hackclub.com/api/amas/) – **all AMAs ever**

### Event Schema
* IDs are UUIDs.
* Descriptions are formatted in markdown.
* `tags` is an array of strings (e.g. `["stardance"]`, `["ama", "workshop"]` ).

### Regular event

```
{
  "id": "8a20db4e-35e8-47a3-a075-d392173a86d9",
  "slug": "code-in-the-dark",
  "title": "Code in the Dark",
  "desc": "On a live Zoom call, we're going to…",
  "leader": "@amogh",
  "cal": "https://www.google.com/calendar/render?action=TEMPLATE&…",
  "start": "2020-04-02T00:00:00.000Z",
  "end": "2020-04-02T01:00:00.000Z",
  "youtube": null,
  "ama": false,
  "amaId": "",
  "amaAvatar": "",
  "avatar": "https://…",
  "tags": ["workshop", "social"]
}
```

### AMA

```
{
  "id": "4f616602-d015-4383-9511-04a890396655",
  "slug": "ama-with-guillermo-rauch",
  "title": "AMA with Guillermo Rauch",
  "desc": "Guillermo is the founder of…",
  "leader": "@lachlanjc",
  "cal": "https://www.google.com/calendar/render?action=TEMPLATE&…",
  "start": "2020-05-14T20:00:00.000Z",
  "end": "2020-05-14T21:00:00.000Z",
  "youtube": "https://youtu.be/PXlDzMMZydk",
  "ama": true,
  "amaId": "recx1wwapHrBPZ3Mq",
  "amaAvatar": "https://dl.airtable.com/.attachmentThumbnails/…",
  "avatar": "https://dl.airtable.com/.attachmentThumbnails/…",
  "tags": ["ama"]
}
```

---


<div id="-screenshots" align="center">
  <h3> App Screenshots</h3>

  <table>
    <tr>
      <td>
        <img src="https://github.com/user-attachments/assets/bdd168f0-0d75-4723-b4f3-7ecf8e846749" width="250" alt="Screenshot 1" style="border-radius: 12px;" />
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/47e33347-c2bc-4aeb-80d9-0441e02df630" width="250" alt="Screenshot 2" style="border-radius: 12px;" />
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/24ebb0c5-117d-4cc2-9aea-35c5a1297f43" width="250" alt="Screenshot 3" style="border-radius: 12px;" />
      </td>
    </tr>
  </table>
</div>

---

<div align="center">
  <h3>POSTER</h3>
  <table>
    <tr>
      <td>
        <img src="https://github.com/user-attachments/assets/2a80183b-e0f7-4a70-b6a2-90b53c03a6dd" width="397" height="561" alt="Poster Design">
      </td>
    </tr>
  </table>
</div>

---

##  Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any improvements you make to enhance this project are greatly appreciated!

### How to Contribute:

1. **Fork** the Project
2. **Create** your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your Changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the Branch (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

I will gladly review your changes and merge them into the project. Thank you for helping make this app even better.

<a href="https://hackclub.com/"><img style="position: absolute; top: 0; left: 10px; border: 0; width: 256px; z-index: 999;" src="https://assets.hackclub.com/flag-orpheus-left.svg" alt="Hack Club"/></a>

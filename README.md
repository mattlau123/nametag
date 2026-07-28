# NameTag Manager v1.1 — User Guide

A simple guide for creating and updating the e-ink name displays.
No technical knowledge needed.

---

## 1. What this tool does

**NameTag Manager** lets you design name tags on screen and send them, over
Bluetooth, to the small e-ink name displays. You can make:

- **one tag at a time** (Single), or
- **many tags at once** (Batch).

It is a single file that opens in your web browser. It needs **no internet**, no
installation, and no account. Your work is saved automatically on the device you
use.

---

## 2. What you need

| Device | Design a tag? | Send to a display? | Notes |
|---|---|---|---|
| **Computer** (Windows or Mac) | ✅ Yes | ✅ Yes | **Best choice.** Use **Chrome** or **Edge**. |
| **Android** phone or tablet | ✅ Yes | ✅ Yes | Open it in the **Chrome** app. |
| **iPhone / iPad** | ✅ Yes | ⚠️ Not from Safari | You can design tags, but Apple's browser cannot send over Bluetooth. To send, use a computer or an Android phone. *(Advanced: a free browser app called “Bluefy” can add this ability on iPhone.)* |

You will also need:

- The **e-ink name displays**, switched on and nearby (within about one metre
  while sending).
- The **NameTag Manager** file (one file, e.g. `nametag_v1.1.html`).

> **Tip:** The simplest, most reliable set-up is a computer or an Android phone
> with the **Chrome** browser. Everything in this guide works the same way on
> all of them.

---

## 3. Open the tool on your device

The tool is one file. Opening it is like opening a document.

**On a computer**

1. Double-click the **NameTag Manager** file.
2. It opens in your browser. If it opens in the wrong browser, right-click the
   file → **Open with** → **Google Chrome** (or **Microsoft Edge**).

**On an Android phone or tablet**

1. Copy the file onto the phone (for example into **Downloads** or **Files**).
2. Tap the file. If asked which app to use, choose **Chrome**.

**On an iPhone or iPad**

1. Save the file into the **Files** app.
2. Tap it to open it in Safari — you can now **design** tags.
3. To **send** a design to a display, use a computer or an Android phone
   (see the table in Section 2).

> Your **Batch** list — organisations, people and display assignments — is
> **saved automatically** on that device, so it is still there the next time you
> open the file on the same device.

---

## 4. Get your displays ready

1. **Keep each display powered — connect it to its battery.** The displays use
   up battery quickly, so always keep them charged or plugged in. A flat battery
   is the most common reason a display does not appear when you try to connect.
2. Every display has its own number — **BADGE0001**, **BADGE0002**, and so on
   (up to BADGE0020) — shown on a label on the display. Read the label to see
   which display you are holding; this is how you pick the right one when
   sending.
3. Just before you connect a display, you will **press its reset button** once
   (see Section 7, Step 2). This makes it show up in the connection list, and
   keeps its Bluetooth on for about **10 minutes** — after that the display
   sleeps to save battery (the name stays on screen). Press reset again to
   reconnect.

---

## 5. Make ONE name tag (Single)

Use this when you just need a single tag.

1. At the top of the screen, tap **Single NameTag**.
2. Fill in the boxes: **Name**, **Title / Posting**, and
   **Organisation / Company**.
3. *(Optional)* Add a logo: **drag a picture onto the logo box**, **paste** one
   (Ctrl/⌘+V), or **click the box** to choose a file. Adjust **Logo size** if you
   want it bigger or smaller. To remove a logo, add a different one.
4. Choose a **NameTag layout** — this decides where the logo and text sit:
   *Logo top, text below*; *Logo left, text right*; *Logo top-left, text center*;
   or *Text only* (no logo).
5. *(Optional)* Fine-tune the look with the switches:
   - **Swap Title / Organisation** — puts the organisation line above the title.
   - **Red accent line** — turn this **off** for a plain look with no red bar
     under the text (it is on by default).
6. The **preview** shows exactly what the display will show. Long names shrink
   automatically so they always fit.
7. To send it to a display, follow **Section 7**.
8. *(Optional)* **Save as batch template** stores this exact design — layout,
   sizes, swap, and red-line choice — so you can reuse it for a whole batch. It
   then appears as the **★ Custom** card in Batch mode (see Section 6, Step 4).
9. *(Optional)* **Download PNG** saves a picture of the tag to your device.
   **Reset** clears the form to start again.

---

## 6. Make MANY name tags at once (Batch)

Use this for an event or a whole team. There are four short steps on screen.

> On a computer the tool usually opens straight into **Batch NameTags**. On a
> phone it opens into **Single** — just tap **Batch NameTags** at the top.

### Step 1 — Organisations
This is where you add each company/department (and its logo, if any).

1. Type an **Organisation name** (for example, the company or team).
2. *(Optional)* Add its logo: **drag a picture onto the box**, or **tap the box**
   to choose a picture (“*Drag & drop, paste, or click to add a logo*”).
3. Tap **Add organisation**. It now appears as a small card.
4. Repeat for each organisation. An organisation with **no logo** is fine — its
   tags simply show clean, centred text.

### Step 2 — People
1. Tap **+ Add Person**. A new row appears.
2. Fill in the person’s **Name** and **Title / Posting**, and choose their
   **Organisation** from the drop-down list (or **None**).
3. To add lots of people quickly, tap **Paste Names** and paste one person per
   line in the form:
   `Name | Title | Organisation`
   (An organisation name only links if you already added it in Step 1; otherwise
   the person is set to **None**.)

### Step 3 — Assign NameTags
Decide which physical display each person gets.

1. In each person’s row, use the **Assigned NameTag** drop-down to pick a display
   number (for example **BADGE0003**).
2. Tap **Find / Add NameTag** to connect a display over Bluetooth (see
   **Section 7**). Connect each display once.
3. *(If a display drops out)* tap **Reconnect NameTags**.

### Step 4 — Preview & Upload
1. Choose a **Badge template** by tapping one of the picture cards. This layout
   applies to **everyone** in the batch. There are four choices:
   - The three built-in layouts (*Logo top*, *Logo left*, *Logo top-left*).
   - **★ Custom** — the design you saved in Single mode with **Save as batch
     template**. This card stays greyed out until you have saved one. To change
     it, tap **Edit custom in Single mode →**, adjust the design, and save again.
2. Tap **Preview** on any person’s row to check how their tag looks.
3. When your displays are connected and assigned, tap **Upload All Ready** to
   send to all of them at once. A **progress bar appears at the bottom of the
   screen** so you can see it working.

Two more buttons help here:

- **Upload Selected** — sends only the rows you have ticked.
- **Retry Failed** — sends again any that did not go through.

### Advanced — prepare a big list in Excel (spreadsheet)

If you already keep your people in **Excel**, you can bring them all in at once
instead of typing each person. In Batch mode, open **Advanced / CSV tools** at
the bottom of the page.

1. Tap **Download NameTag CSV Template**. This gives you a spreadsheet file with
   the correct column headings already set up.
2. Open it in Excel and fill in **one row per person**. The columns are:

| Column | What to put in it |
|---|---|
| **name** | The person’s name. |
| **title** | Title / posting (optional). |
| **organisation** | The organisation’s name. It must **exactly match** an organisation you added in Step 1, or the person is left as “None” (optional). |
| **device** | The display for that person, for example `BADGE0003`. Leave blank to let the tool choose one (optional). |
| **extra1, extra2, extra3** | Up to three extra lines of text (optional). |

3. In Excel, choose **Save As** and pick the **CSV** (comma separated) format.
4. Back in the tool, tap **Import CSV** and choose your saved file. Your people
   appear in the table, ready to assign displays and send.

> **Before you import:** add your **organisations and logos first** (Step 1), so
> the organisation names in your spreadsheet link up. Importing **replaces** the
> people currently in the list.

The same **Advanced / CSV tools** area has three more buttons:

- **Export People CSV** — saves your current list to a spreadsheet (a handy backup).
- **Download Upload Report** — saves a record of what was sent to each display.
- **Clear Batch** — removes all people (your saved organisations stay).

---

## 7. Send a design to a display (Bluetooth)

This is the same idea in both Single and Batch mode.

**First, get the display ready to connect:**

1. Make sure the display has **power — connect it to its battery.** (A flat
   battery is the most common reason a display will not appear.)
2. **Press the reset button on the display once.** Only after a reset will its
   name (for example **BADGE0001**) appear in the connection list. Bluetooth then
   stays on for about **10 minutes**, so do your uploads within that window. After
   10 minutes the display sleeps to save battery (the name stays on screen) — just
   press reset again to reconnect.

**Then connect and send:**

3. The first time, your browser asks for permission to use **Bluetooth** — tap
   **Allow**.
4. **In Single mode:** tap **Connect Bluetooth**, pick the display (for example
   **BADGE0001**) from the list that appears, then tap **Upload to NameTag**.
5. **In Batch mode:** tap **Find / Add NameTag**, pick the display from the list,
   then use **Upload All Ready** or **Upload Selected**.
6. Keep the display **switched on and close by** (about one metre) while sending.
7. It takes a few seconds. The display’s screen refreshes and the new name tag
   appears. Done!

> Each reset gives you about **10 minutes** of Bluetooth. If a display
> disconnects, doesn't appear, or its 10 minutes have passed (it sleeps to save
> battery), **press its reset button again**, then tap **Connect Bluetooth**
> (Single) or **Reconnect NameTags** (Batch).

---

## 8. Handy tips

- **Long names fit automatically.** The text shrinks to stay inside the tag, so
  you never have to adjust sizes by hand.
- **The preview is exactly what you’ll get.** What you see on screen is what the
  display will show.
- **Your batch list is saved on the device.** Close and reopen the file on the
  same device and your organisations, people and display assignments are still
  there. *(A single one-off tag is not saved — send or download it before
  closing.)*
- **Switch modes any time** using **Single NameTag** / **Batch NameTags** at the
  top.
- **No logo is fine.** Tags without a logo show neat, centred text.
- **Displays save battery on their own.** Bluetooth switches off about 10 minutes
  after a reset, and the name stays on screen — so a charged display lasts a long
  time. Just press reset when you need to update it again.

---

## 9. If something doesn’t work

| What you see | What to do |
|---|---|
| “Bluetooth is unavailable” or you can’t connect | Use **Chrome** (Android) or **Chrome/Edge** on a computer. An iPhone’s Safari cannot send to displays. |
| The display isn’t in the connect list | Check it has **battery/power**, and remember Bluetooth only stays on ~10 min per reset. **Press its reset button** once, then tap **Find / Add NameTag** (or **Connect Bluetooth**) again. |
| You tapped **Upload All Ready** but nothing happens | Check the displays are **connected** and **assigned** to people. Only connected, assigned tags are sent. |
| The wrong display updated | Check the **BADGE number** you picked matches the label on the display. |
| Text looks small on a long name | That is normal — it shrinks to fit. Use a shorter title if you want it larger. |
| You want to start over | Single mode: **Reset**. Batch mode: **Clear Batch** (this removes people; your saved organisations stay). |

---

*Quick reference — the four batch steps:*
**1) Organisations → 2) People → 3) Assign NameTags → 4) Preview & Upload.**

# Path of Exile 2 Campaign Guides for Exile-UI

These JSON files are custom POE2 campaign guides Update **0.5** used for **Act-Tracker** with Exile-UI. Each guide combines a fast campaign route with build-specific skill, support-gem, equipment, boss, and ascendancy instructions.

## Available guides

| File                                           | Build                                  |
| ---------------------------------------------- | -------------------------------------- |
| `Campaign Guide Generic.json`                  | Class-neutral campaign route           |
| `Campaign Guide Grenade Build.json`            | Mercenary Grenade — **GuyThatDies**    |
| `Campaign Guide Ice Shot Build.json`           | Ice Shot Deadeye — **FubGun**          |
| `Campaign Guide Monk Build.json`               | Glacial Cascade Monk — **GuyThatDies** |
| `Campaign Guide Mercenary Twisters Build.json` | Mercenary Twisters — **GuyThatDies**   |
| `Campaign Guide Huntress Twisters Build.json`  | Huntress Twisters — **GuyThatDies**    |
| `Campaign Guide Varashta Build.json`           | Disciple of Varashta — **GuyThatDies** |

## Credits

**Build and guide information:**
Huge thanks to **GuyThatDies** and **FubGun** for their build guides, knowledge, and contributions to the Path of Exile 2 community. These campaign guides use and adapt information from their work.

All credit for the original build concepts, recommendations, and source material belongs to their respective creators. This project focuses on adapting that information into campaign guides for use with the **Exile-UI Act-Tracker**.

Thank you to **GuyThatDies** and **FubGun** for sharing your work with the community!

## Exile-UI

These campaign guides are designed to be used with **Exile-UI** and its **Act-Tracker**.

You can download Exile-UI from its official GitHub repository:

**[Download Exile-UI](https://github.com/Lailloken/Exile-UI)**

For installation instructions, updates, and the latest version, please refer to the official Exile-UI repository.

## Requirements

- Path of Exile 2
- Exile-UI with the Act-Tracker enabled
- A text editor such as Notepad, Notepad++, or Visual Studio Code

## Importing a guide

Exile-UI imports custom guides from the clipboard. It does not open the JSON file directly.

1. Start Exile-UI.
2. Open **Settings**.
3. Open the **Act-Tracker** section.
4. Create a guide slot with the `+` button, or select an unused slot.
5. Open the JSON file for your build in a text editor.
6. Select the entire file with `Ctrl+A` and copy it with `Ctrl+C`.
7. Return to Exile-UI and press **Import** for the selected guide slot.
8. Give the slot a recognizable name, such as `Ice Shot` or `Varashta`.
9. Add your character name if you want Exile-UI to track character level and experience.
10. Enable the Act-Tracker and display its guide overlay.

## Using the guide during the campaign

- **GENERAL** contains campaign routing, quest objectives, permanent rewards, level targets, and zone transitions.
- The build-named section contains skills, supports, equipment upgrades, boss rotations, and ascendancy instructions for that build.
- Exile-UI reads the Path of Exile 2 client log and automatically advances when you enter the area referenced by the current page.
- Use the Act-Tracker page controls if a page does not advance automatically or if you complete objectives in a different order.
- The interludes may be completed in a different order from their internal Exile-UI numbering. Use the page or section controls to select the interlude you are currently running.

## Updating an imported guide

Exile-UI stores its own imported copy. Replacing the JSON file on disk does not update an existing guide slot.

To install a newer version:

1. Open the updated JSON file and copy all of its contents.
2. Select the corresponding guide slot in Exile-UI.
3. Import the updated clipboard contents again.
4. If Exile-UI does not replace the slot, create a new slot, import there, and delete the old slot after confirming the new guide works.

Keep the downloaded JSON files as backups. Deleting an Exile-UI guide slot removes its imported copy.

## Troubleshooting

### Import does nothing

- Confirm that the complete JSON file—not its filename or file path—is on the clipboard.
- Do not add or remove characters from the JSON.
- Create a fresh guide slot and try importing again.

### The overlay is not visible

- Enable the Act-Tracker module and its guide overlay in Exile-UI settings.
- Check the overlay position and move it if it is outside your visible game area.
- Run Path of Exile 2 in the display mode supported by your Exile-UI configuration.

### The guide does not advance

- Confirm Exile-UI can read the correct Path of Exile 2 `Client.txt` log.
- Ensure the character name assigned to the guide slot is correct.
- Advance manually with the Act-Tracker page controls when necessary.

### Text is cut off

- Increase the guide width or adjust the Act-Tracker font and scaling settings.
- Move the overlay to a location with enough vertical space.

## Notes

- These files are Exile-UI custom-guide JSON files; they are not Mobalytics `.build` files.
- Campaign layouts and game balance can change between Path of Exile 2 patches.
- Always follow current in-game quest requirements if they differ from an older guide instruction.

# MAD Database for MiSTer

Auto-Generated json DB file at: https://github.com/theypsilon/MAD_Database_MiSTer/tree/db

## How to generate your own MAD Database:

1. Create your own public repository on GitHub
2. Place the contents of this zip (https://github.com/theypsilon/MAD_Database_MiSTer/archive/refs/heads/main.zip) on your new public repository as-is
3. Make sure that there is a .github hidden folder there, if there isn't go back to Step 2, cause something was not copied correctly.
4. Substitute the contents of the mad folder with files of your own. The folder structure inside mad does not matter, it will just look for files with the .mad extension.
5. Commit and push the changes.
6. After 5 mins, your new repository will generate a new branch named db by itself, this is an automatic task. It will contain the zipped json that we need in the [Arcade Organizer](https://github.com/theypsilon/_arcade-organizer/).

## MAD Schema

MAD files are XML files that have to be validated against [this schema](mad_schema.xsd).

An example of a valid MAD file would be the following:

```xml
<?xml version="1.0" ?>
<misterarcadedescription>

	<setname>ddonpachj</setname>
	<name>DoDonPachi (Japan)</name>
	<region>Japan</region>
	<version>1997 2/5 Master Ver.</version>
	<alternative>yes</alternative>
	<parent_title>DoDonPachi</parent_title>
	<platform>Cave 68000</platform>
	<series>DonPachi</series>
	<homebrew>no</homebrew>
	<bootleg>no</bootleg>
	<year>1997</year>
	<manufacturer>Cave,Atlus</manufacturer>
	<category>Shooter - Vertical</category>
	<best_of>theypsilon Top Shmups|1</best_of>

	<rotation>vertical (ccw)</rotation>
	<flip>no</flip>
	<resolution>15kHz</resolution>

	<players>2 (simultaneous)</players>
	<move_inputs>8-way</move_inputs>
	<special_controls></special_controls>
	<num_buttons>3</num_buttons>

</misterarcadedescription>
```

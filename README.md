# Mist Survival FOVFix
Allows choosing of higher than 90 FOV in Mist Survival (Up to 110)
![image](https://github.com/TheRealBeef/Mist-Survival-FOV-Fix/assets/84393940/dacf2ca8-6b60-4138-b351-dc981d9cd635)


# Instructions
Drop the FOVFix_P.pak file into your `\Steam\steamapps\common\Mist Survival\MistSurv\Content\Paks` folder and that's it

# Known issues
Sometimes FOV resets to 90 instead of say 110 when pressing escape ... just press escape again and it goes back to your setting - I'll look into this another day

# How I created it
1. Generated .usmap with UE4SS
2. Use FModel to extract the `MistSurv\Content\AntizeMenuSystem\Widgets\W_Options` .uasset and .uexp files
3. Hex edit the SliderValueMax and SliderMultiply values from 90.0 to 110.0
4. Repack with repak and we're all done

# NovelAI-gensets
Generation setting presets by me for NAI models. My work and a lot of other useful content published by users is available on their discord.  
https://discord.gg/novelai

# The Preset Series
I primarily use prosey AI generators to write stories and have a bunch of lorebooks set up to enforce my style and diversify the story vocabulary. Presets with minimal temperature and repetition penalty tweaks are good for allowing the base strengths of the model to shine. The tweaked samplers are only used as a mitigation strategy against looping that may occur when hitting generate multiple times in a row. Every model needs their own preset and finetuning. The Preset series always follows the same concept and principles though. If you have downloaded one of my Presets before, I recommend grabbing the version provided here on github. I updated and sometimes tweaked the values for this release, so they may differ from old verions I posted on discord.  

If a model has the option to "Use Default Whitelist" for tokens, make sure that it is enabled. If you use many important character lorebooks, make sure "dynamic repetition penalty range" or DRPR is turned on.  

# Kayrastyle
NovelAI's new models based on their NAILM base once again have unique weights for how the sliders behave with them. I tried implementing the Preset concept for them, but quickly discovered I can get better outputs by pushing setting values higher than I usually would. The end result of experimentation was Kayrastyle, a preset I named because I started pursuing ways how to more easily reach the amazing heights their latest Kayra model can reach on some outputs.

Kayrastyle uses conventional sampling methods before NovelAI added new ones to their stack. It's a very comfortable generation preset similar to previous renditions of the Preset in my opinion.  
  
Kayrastyle Unleashed is my latest and greatest generation preset, integrating mirostat sampling values optimized together with Basileus. You should definitely use it for Kayra, maybe even move the values over to Clio if you still use the smaller model. As with previous presets, if you're using many Lorebooks, you should turn on DRPR and the default token whitelist. This is especially true if you're on the Scroll or Tablet subscription.  

# Other Presets
Other presets I found useful are shared as well. They tend to be tweaks on the default presets. If you find a preset here with a name from the default NovelAI gensets, it's closely based on the original, with tweaks that I personally found to perform better and result in more enjoyable prose generations.
Sigurd and older models do not have presets provided by me here. This is because the default Storywriter preset provided in NAI is my original work, based on a paper I read about settings that researchers found optimal for the GPT2XL model.

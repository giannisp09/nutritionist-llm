# nutritionist-llm
An LLM finetuned on high rating recipes. 

SFT.ipynb dives into a recipes dataframe, and another dataframes consisting of users reviews of the recipes.
It merges abd group them, having an average review per recipe, that is used as reward.
Then it filters recipes based on a specific threshold, and uses the filtered data to perfrom
the fine-tuning. the idea has the same flow as the Filtered Behavioural Clloning.

import os
import re
import nltk
# import enchant
from nltk.corpus import stopwords
import collections



def check_stop_words(text):
	import os
import re
import nltk
# import enchant
from nltk.corpus import stopwords
import collections



def check_stop_words(text):
	
	other_words=["ttyl","am","pm","its","ya","dosent","still","hi"]
	
	filtered_text=re.compile('[a-zA-Z]+').findall(text)
	# print filtered_text
	
	filtered_text=[x for x in filtered_text if x not in other_words]
	# print filtered_text
	filtered_text=[x for x in filtered_text if len(x)>2]
	# print filtered_text
	stopwords=nltk.corpus.stopwords.words('english')
	content=[w.lower() for w in filtered_text]
	# print content
	content=[w for w in content if w.lower() not in stopwords]
	content=list(set(content))
	# print content
	content=" ".join(content)
	return content
#test
# print check_stop_words("this it pheonix pheonix lunch 8942 t _8 of han h")

	filtered_text=re.compile('[a-zA-Z]+').findall(text)
	# print filtered_text
	
	filtered_text=[x for x in filtered_text if x not in other_words]
	# print filtered_text
	filtered_text=[x for x in filtered_text if len(x)>2]
	# print filtered_text
	stopwords=nltk.corpus.stopwords.words('english')
	content=[w.lower() for w in filtered_text]
	# print content
	content=[w for w in content if w.lower() not in stopwords]
	content=list(set(content))
	# print content
	content=" ".join(content)
	return content
#test
# print check_stop_words("this it pheonix pheonix lunch 8942 t _8 of han h")

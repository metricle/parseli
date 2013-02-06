Parseli
=======

A suite of modules for parsing linkedin public pages into clean json

Demo
----

    >>> from parseli import getli
    >>> getli('http://linkedin.com/in/mekarpeles')
    <Storage {'name': {'given-name': u'Mek', 'family-name': u'Karpeles'}, 'headline': u'Founder at Hackerlist', 'similar': [u'http://www.linkedin.com/in/jeffweiner08', u'http://www.linkedin.com/in/sbalaban?trk=pub-pbmap', u'http://www.linkedin.com/in/sbalaban?trk=pub-pbmap', u'http://www.linkedin.com/in/michaelsiedlecki?trk=pub-pbmap', u'http://www.linkedin.com/in/michaelsiedlecki?trk=pub-pbmap', u'http://www.linkedin.com/pub/zephyr-pellerin/39/938/515?trk=pub-pbmap', u'http://www.linkedin.com/pub/zephyr-pellerin/39/938/515?trk=pub-pbmap', u'http://www.linkedin.com/in/turian?trk=pub-pbmap', u'http://www.linkedin.com/in/turian?trk=pub-pbmap', u'http://www.linkedin.com/in/kevingao1?trk=pub-pbmap', u'http://www.linkedin.com/in/kevingao1?trk=pub-pbmap', u'http://www.linkedin.com/pub/zachary-crockett/24/568/521?trk=pub-pbmap', u'http://www.linkedin.com/pub/zachary-crockett/24/568/521?trk=pub-pbmap', u'http://www.linkedin.com/in/michaelazamloot?trk=pub-pbmap', u'http://www.linkedin.com/in/michaelazamloot?trk=pub-pbmap', u'http://www.linkedin.com/in/jjuran?trk=pub-pbmap', u'http://www.linkedin.com/in/jjuran?trk=pub-pbmap', u'http://www.linkedin.com/pub/gavin-knight/46/732/2b1?trk=pub-pbmap', u'http://www.linkedin.com/pub/gavin-knight/46/732/2b1?trk=pub-pbmap', u'http://www.linkedin.com/in/sashyrichmond?trk=pub-pbmap', u'http://www.linkedin.com/in/sashyrichmond?trk=pub-pbmap'], 'industry': u'Internet', 'url': 'http://linkedin.com/profile?id=112557365', 'location': {'area': '', 'locality': u'San Francisco Bay Area'}, 'education': [{'major': u'Computer Science', 'dtstart': u'2010-01-01', 'dtend': u'2015-12-31', 'institution': u'Unviersity of Delaware', 'degree': u'Ph.D Computer and Information Systems (On Leave)'}, {'major': u'Computer Science', 'dtstart': u'2006-01-01', 'dtend': u'2010-12-31', 'institution': u'University of Vermont', 'degree': u'BS Computer Science'}, {'major': '', 'dtstart': u'2002-01-01', 'dtend': u'2006-12-31', 'institution': u'Cheshire High School', 'degree': ''}], 'employment': [{'current': 1, 'date': {'start': u'2012-12-01', 'end': ''}, 'location': u'San Francisco Bay Area', 'institution': u'Hackerlist', 'title': u'Founder and CEO'}, {'current': 0, 'date': {'start': u'2011', 'end': u'2012-10-01'}, 'location': u'San Francisco', 'institution': u'Hyperink', 'title': u'Principal Architect'}, {'current': 0, 'date': {'start': u'2010', 'end': u'2011'}, 'location': u'San Francisco', 'institution': u'Babo Labs', 'title': u'Co-Founder, CTO'}, {'current': 0, 'date': {'start': u'2010-08-01', 'end': u'2011-08-01'}, 'location': '', 'institution': u'University of Delaware', 'title': u'Ph.D Candidate'}, {'current': 0, 'date': {'start': u'1998', 'end': u'2011'}, 'location': u'United States', 'institution': u'Hackathons', 'title': u'Hacker'}, {'current': 0, 'date': {'start': u'2009', 'end': u'2010'}, 'location': '', 'institution': u'University of Vermont', 'title': u'CSSA President'}, {'current': 0, 'date': {'start': u'2007', 'end': u'2009'}, 'location': '', 'institution': u'MicroStrain, Inc.', 'title': u'Intern'}], 'id': '112557365', 'viewers': []}>
    
Installation
------------

   pip install parseli

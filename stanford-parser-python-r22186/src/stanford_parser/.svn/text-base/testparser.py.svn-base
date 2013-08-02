from parser import Parser

class TestParser:
    """Parses the text using stanford-parser"""
    def __init__(self, text):
        self.__parser = Parser()
        self.__text = text

    def getDependencies(self):
        """Returns dependencies list"""
        parsedtext = self.__parser.parseToStanfordDependencies(self.__text)
        return parsedtext.dependencies
    
    

# Imperatives from The Big Bang Theory and Wikipedia Articles for Deletion
This is a corpus with imperative and non-imperative sentences from the TV show *The Big Bang Theory* and Wikipedia Articles for Deletion. We used rule-based classification and manual annotation to classify imperative sentences.

### Data from the TV show
We include both raw data and classified data in this repository. Each file in the raw data is from one episode with each line representing one dialogue from that specific episode. In the tab-separated classification data file, each line represents one dialogue. The columns respectively are: data source (in the formant of nxmm with 'n' indicating the season of the show and 'mm' representing the episode), text, imperative classification (1 for imperative and 0 for non-imperative), imperative category, and whether the imperative sentence has affixal negative markers or not.

### Data from Wikipedia Articles for Deletion
We only include classified data for sentences from this source. The file is tab seperated with two columns of text and classification (1 for imperative and 0 for non-imperative) respectively. Each line represent one instance of data.

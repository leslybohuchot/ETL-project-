{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "***ETL PROJECT***"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "***Data Sources***"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/page/80/\n",
    "\n",
    "https://en.wikipedia.org/wiki/Dengue_fever_outbreaks"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Detailing the process of the extraction, transformation, and loading steps"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "The process was import the data from the drivendata.org competition, I brought both csv files to make comparisons between dengue cases in San Juan, Puerto Rico and the rest of the world.\n",
    "\n",
    "I imported the csv files into python and ran analysis consisting on average temperature, total dengue cases etc. "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "***What data sources you chose, and why***"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "I wanted to choose a meaninful project for a real life problem, so I picked dengue fever because the issue seemed important"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "***Explication why you have performed the types of transformations you did***"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "I wanted to transform the data so it would give an overall analysis of average air temperature and total number of years we are looking at of dengue cases "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "***Why you chose the type of the final database***"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "I chose MongDB because it was more versatile and I wanted to have the freedom to work with the data "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "***Schema of the tables/collections in the final database\n",
    "Hypothetical use cases for your database***\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "This could be used as a quick comparison and would answer the question of \"how does Puerto Rico's dengue cases compare to the rest of the world\"\n",
    "\n",
    "I used dictionaries to look closely at the data and be able to differentiate between the countries that have reported cases of the disease "
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.6.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}

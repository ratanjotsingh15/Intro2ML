# Intro2ML Project

import os
import streamlit as st
import google.generativeai as palm

palm.configure(api_key="<Your API Key>")

model_name = 'models/text-bison-001'

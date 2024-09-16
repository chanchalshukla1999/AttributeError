# AttributeError 
ModuleNotFoundError: No module named 'distutils' resolve this error
Step1: Downgrade Python
Step2: Install the setuptools package(pip install setuptools)
Step3: Install the distutils package from a third-party repository(pip install pydistutils)
Step4: Update your package installer(pip install --upgrade pip)
Step5: Additionally, if you're trying to install PyAudio, you can try using the following command(pip install --global-option='build_ext' --global-option='-I/opt/homebrew/include' --global-option='-L/opt/homebrew/lib' pyaudio --use-deprecated=legacy-resolver
)










FROM microsoft/windowsservercore
RUN net user John B@dP@ssw0rd /ADD
COPY . /
RUN msiexec /quiet /i sample.msi ACCOUNT=%COMPUTERNAME%\John PASSWORD=B@dP@ssw0rd

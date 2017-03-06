Jenkins Docker Agent with Docker Engine
=======================================

## How to use?
You can use as a dynamically provisioned Docker agent. You can specify it as an agent Docker template and need to mark "privileged". 

## Warning
As mentioned by Jérôme Petazzoni on his [blog post](http://jpetazzo.github.io/2015/09/03/do-not-use-docker-in-docker-for-ci/), this method is not a silver bullet. 

## Technical
Technical, this image is a merge of two great works:
* Ervin Varga - https://github.com/evarga/docker-images
* Jérôme Petazzoni - https://github.com/jpetazzo/dind

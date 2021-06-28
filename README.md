# Introduction to Kubernetes Using Docker

### Udemy Course : TRT Rating 2/5 Stars

[Link to Course](https://www.udemy.com/course/introduction-to-kubernetes-using-docker)

This course is outdated, but decent for practice and troubleshooting outdated instructions.  Kubernetes has evolved on Google Cloud to where you should ignore all the information in this course about using K8s Dashboard.  The Dashboards are know essentially the Google Cloud Platform GUI in the Kubernetes Service. 

### Correction Notes

**Section 3: Working with Docker**

- 19. Create Own Images Using Docker
	- Reference Dockerfile in `s3-docker` in this repository to help create a more up to date wordpress site.

**Section 4. All About Kubernetes**
	
- 24. Deploying App to Cluster (3:03)
	- The command is `kubectl expose pod wordpress --type=LoadBalancer` now as of 6/13/2021

**Section 5. Real World Projects**
	
- 26. Creating Cluster GuestBook (6:18)
	- Repository moved here: https://github.com/kubernetes/examples/tree/master/guestbook

- 32. Deploying External IP
	- You need to update the frontend-service.yaml to enable LoadBalancer (he goes over this after claiming it was "perfect"...)
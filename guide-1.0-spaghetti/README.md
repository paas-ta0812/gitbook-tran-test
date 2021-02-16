# PaaS-TA 1.0 가이드 문서

## 플랫폼 설치 가이드

* [설치 파일 다운로드 받기](https://paas-ta.kr/download/package?query=&query_type=all&query_type1=all&query_type2=&start=6&display=10)
* 개인 환경 설치
  * [BOSH-Lite](https://github.com/paas-ta0812/gitbook-trans-test/tree/6a20e8c8c3860f2d2b91a044caf15a02dd814297/guide-1.0-spaghetti/Install-Guide/BOSH%20Lite/OpenPaaS_PaaSTA_BOSH_Lite_install_guide.md)
* 운영 환경 설치
  * BOSH 설치\([AWS](https://github.com/paas-ta0812/gitbook-trans-test/tree/6a20e8c8c3860f2d2b91a044caf15a02dd814297/guide-1.0-spaghetti/Install-Guide/BOSH/OpenPaaS_PaaSTA_BOSH_AWS_install_guide.md), [OpenStack](https://github.com/paas-ta0812/gitbook-trans-test/tree/6a20e8c8c3860f2d2b91a044caf15a02dd814297/guide-1.0-spaghetti/Install-Guide/BOSH/OpenPaaS_PaaSTA_BOSH_Openstack_install_guide.md)\)
  * Controller 설치\([vSphere](https://github.com/paas-ta0812/gitbook-trans-test/tree/6a20e8c8c3860f2d2b91a044caf15a02dd814297/guide-1.0-spaghetti/Install-Guide/Controller/Controller_vSphere_install_guide.md),

    [AWS](https://github.com/paas-ta0812/gitbook-trans-test/tree/6a20e8c8c3860f2d2b91a044caf15a02dd814297/guide-1.0-spaghetti/Install-Guide/Controller/Controller_AWS_install_guide.md), [Openstack](https://github.com/paas-ta0812/gitbook-trans-test/tree/6a20e8c8c3860f2d2b91a044caf15a02dd814297/guide-1.0-spaghetti/Install-Guide/Controller/Controller_Openstack_install_guide.md)\)

  * Container 설치\([vSphere](https://github.com/paas-ta0812/gitbook-trans-test/tree/6a20e8c8c3860f2d2b91a044caf15a02dd814297/guide-1.0-spaghetti/Install-Guide/Container/Container_vSphere_install_guide.md),

    [AWS](https://github.com/paas-ta0812/gitbook-trans-test/tree/6a20e8c8c3860f2d2b91a044caf15a02dd814297/guide-1.0-spaghetti/Install-Guide/Container/Container_AWS_install_guide.md),

    [Openstack](https://github.com/paas-ta0812/gitbook-trans-test/tree/6a20e8c8c3860f2d2b91a044caf15a02dd814297/guide-1.0-spaghetti/Install-Guide/Container/Container_Openstack_install_guide.md)\)
* 플랫폼 설치
  * [플랫폼 설치 자동화](https://github.com/paas-ta0812/gitbook-trans-test/tree/6a20e8c8c3860f2d2b91a044caf15a02dd814297/guide-1.0-spaghetti/Install-Guide/Platform%20Install%20System/OpenPaaS_PaaSTA_Platform_Install_System_install_guide.md)

## 서비스 설치 가이드

* DBMS 설치
  * Cubrid \( [vSphere](service-guide/dbms/openpaas_paasta_servicepack_cubrid_vsphere_install_guide.md), 

    [AWS](service-guide/dbms/openpaas_paasta_servicepack_cubrid_aws_install_guide.md), 

    [OpenStack](service-guide/dbms/openpaas_paasta_servicepack_cubrid_openstack_install_guide.md), 

    [Bosh-Lite](service-guide/dbms/openpaas_paasta_servicepack_cubrid_bosh-lite_install_guide.md)\)

  * Mysql \([vSphere](service-guide/dbms/servicepack_mysql_vsphere_install_guide.md), 

    [AWS](service-guide/dbms/servicepack_mysql_aws_install_guide.md), 

    [OpenStack](service-guide/dbms/servicepack_mysql_openstack_install_guide.md), 

    [Bosh-Lite](service-guide/dbms/servicepack_mysql_bosh-lite_install_guide.md)\)
* NOSQL 설치
  * Mongodb \([vSphere](service-guide/nosql/openpaas_paasta_servicepack_mongodb_vsphere_install_guide.md), 

    [AWS](service-guide/nosql/openpaas_paasta_servicepack_mongodb_aws_install_guide.md), 

    [OpenStack](service-guide/nosql/openpaas_paasta_servicepack_mongodb_openstack_install_guide.md), 

    [Bosh-Lite](service-guide/nosql/openpaas_paasta_servicepack_mongodb_bosh-lite_install_guide.md)\)

  * Redis \([vSphere](service-guide/nosql/servicepack_redis_vsphere_install_guide.md), 

    [AWS](service-guide/nosql/servicepack_redis_aws_install_guide.md), 

    [OpenStack](service-guide/nosql/servicepack_redis_openstack_install_guide.md), 

    [Bosh-Lite](service-guide/nosql/servicepack_redis_bosh-lite_install_guide.md)\)
* Storage 설치
  * GlusterFS \([vSphere](service-guide/storage/openpaas_paasta_servicepack_glusterfs_vsphere_install_guide.md), 

    [AWS](service-guide/storage/openpaas_paasta_servicepack_glusterfs_aws_install_guide.md), 

    [OpenStack](service-guide/storage/openpaas_paasta_servicepack_glusterfs_openstack_install_guide.md), 

    [Bosh-Lite](service-guide/storage/openpaas_paasta_servicepack_glusterfs_bosh-lite_install_guide.md)\)
* MasageQueue 설치
  * RabbitMQ \([vSphere](service-guide/messagequeue/servicepack_rabbitmq_vsphere_install_guide.md), 

    [AWS](service-guide/messagequeue/servicepack_rabbitmq_aws_install_guide.md), 

    [OpenStack](service-guide/messagequeue/servicepack_rabbitmq_openstack_install_guide.md), 

    [Bosh-Lite](service-guide/messagequeue/servicepack_rabbitmq_bosh-lite_install_guide.md)\)
* API Platform 설치
  * WSO2\([vSphere](service-guide/etc/servicebroker_apiplatform_vsphere_install_guide.md), 

    [AWS](service-guide/etc/servicebroker_apiplatform_aws_install_guide.md), 

    [OpenStack](service-guide/etc/servicebroker_apiplatform_openstack_install_guide.md), 

    [Bosh-Lite](service-guide/etc/servicebroker_apiplatform_bosh_lite_install_guide.md)\)

## 활용 가이드

* [BOSH CLI\(Command Line Interface\) 사용](use-guide/openpaas_paasta_bosh_cli_guide.md)
* [CF CLI\(Command Line Interface\) 사용](use-guide/openpaas-cli-guide.md)
* \[Eclipse plugin 개발도구 사용\] \(./Use-Guide/Open\_PaaS\_develop\_guide.md\)

## 개발 언어 별 어플리케이션 가이드

* [Node.js](sample-app-guide/openpaas_paasta_application_nodejs_develope_guide.md)
* [PHP](sample-app-guide/openpaas_paasta_application_php_develope_guide.md)
* [Python](sample-app-guide/openpaas_paasta_application_python_develope_guide.md)
* [Ruby](sample-app-guide/openpaas_paasta_application_ruby_develope_guide.md)
* [Java](sample-app-guide/openpaas_paasta_application_java_develope_guide.md)
* [Go](sample-app-guide/openpaas_paasta_application_go_develope_guide.md)

## 플랫폼 개발 가이드

* [스템셀 개발 가이드](development-guide/openpaas_paasta_build_stemcell_guide.md)
* [서비스팩 개발 가이드](development-guide/servicepack_develope_guide.md)
* [빌드팩 개발 가이드](development-guide/buildpack_develope_guide.md)
* [어플리케이션 APIPlatform 도로주소 개발 가이드](development-guide/application_apiplatform_dorojuso_devlope_guide.md)
* [퍼블릭 API 개발 가이드](development-guide/publicapi_devlope_guide.md)


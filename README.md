# go logger

Extension module of golang logging

```go
import log "gopkg.in/logger.v1"

func main(){
  log.SetOutputLevel(log.Ldebug)
  log.Debugf("Debug: foo\n")
	log.Debug("Debug: foo")

	log.Infof("Info: foo\n")
	log.Info("Info: foo")

	log.Warnf("Warn: foo\n")
	log.Warn("Warn: foo")

	log.Errorf("Error: foo\n")
	log.Error("Error: foo")

	log.SetOutputLevel(Linfo)

	log.Debugf("Debug: foo\n")
	log.Debug("Debug: foo")

	log.Infof("Info: foo\n")
	log.Info("Info: foo")

	log.Warnf("Warn: foo\n")
	log.Warn("Warn: foo")

	log.Errorf("Error: foo\n")
	log.Error("Error: foo")
}

```
